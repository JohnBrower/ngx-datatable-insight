# ngx-datatable for Insight

Geforktes Repository von @swimlane/ngx-datatable mit Modifikationen/Bugfixes für Nutzung in Insight.

* Original Readme siehe: https://github.com/swimlane/ngx-datatable/blob/master/README.md
* Original Repository siehe: https://github.com/swimlane/ngx-datatable

* Build neu Auszuführen mit "npm run package"

###Änderungen (Stand 5.8.2019)

* Basiert auf Coomit '(release): 15.0.2 [ad3af3c1]'
* Kein Fehler bei Header-Selektion über ~100.000 Zeilen

* ggf. TODO: 
    * Spalten (Columns) enthalten zusätzliches Property colID zur Identifikation 

        * src/components/columns/column.directive.ts:
            * 15 @Input() colID: any; // NEU!!!

        * src/types/table-column.type.ts
             * colID: any; // NEU!!!
