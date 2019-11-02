# ngx-datatable for Insight

Geforktes Repository von @swimlane/ngx-datatable mit Modifikationen/Bugfixes für Nutzung in Insight.

* Original Readme siehe: https://github.com/swimlane/ngx-datatable/blob/master/README.md
* Original Repository siehe: https://github.com/swimlane/ngx-datatable

* Build neu Auszuführen mit "npm run package"

###Änderungen (Stand 05.08.2019)

* Basiert auf Commit '(release): 15.0.2 [ad3af3c1]'
* Kein Fehler bei Header-Selektion über ~100.000 Zeilen

###Änderungen (Stand 02.11.2019)

* Spalten (Columns) enthalten zusätzliches Property colID zur Identifikation 

    * src/components/columns/column.directive.ts[17]:  @Input() colID?: string;
    * src/types/table-column.type.ts[47]: colID?: string;
