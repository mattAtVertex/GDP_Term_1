# GDP Milestone 6 Resources

<p>Blueprint can be used to create tools that artists and designers can use to speed up their workflow. The ability to use Blueprint to create tools like this is really only limited by an individuals imagination. We will explore ways to build tools that will speed up your development time.</p>
<p><strong>Data Driven Gameplay</strong> - <span>Data driven gameplay helps mitigate the amount of work and complexity involved, as well as providing the ability to visualize and parameterize data creation and progression, for games that have an extended lifetime well beyond that of a typical boxed game, and require constant tweaking and balancing of data based on player feedback. The ability to move data out to&nbsp;</span><strong>Microsoft Excel</strong><span>&nbsp;or other spreadsheet documents that can be maintained using proven tools and then imported to automatically take effect in the game.</span></p>
<p>There are two new ways that data can be imported into UE4 through Excel documents:</p>
<ul>
<li class="Default">
<p><strong>DataTables</strong></p>
</li>
<li class="Default">
<p><strong>CurveTables</strong></p>
</li>
</ul>
<p>These Excel documents are .xlsm (macro enabled Excel documents) that have macro based export buttons to enable easily exporting to the intermediate data format, comma separated variables (.csv). These documents all reside in a single location to help make data easy to find and modify.</p>
<p><strong>Data Tables</strong> - <span>DataTables, as the name implies, is a table of miscellaneous but related data grouped in a meaningful and useful way, where the data fields can be any valid UObject property, including asset references. Before a designer can import a CSV file into a DataTable, a programmer has to create the row container telling the engine how to interpret the data. These tables consist of column names that have a 1:1 mapping to a given code based UStruct and its variables, which must inherit from&nbsp;</span><strong>FTableRowBase</strong><span>&nbsp;to be recognized by the importer.</span></p>
<p>&nbsp;</p>
<p>Database driven modular design and theming -&nbsp;</p>
<p>&nbsp;</p>
<p><strong>Spline Component</strong> - A spline component is a component in a Blueprint that will allow the propagation of meshes. A practical example of this is creating a construction blueprint that will allow the use of a spline to procedurally "grow" pipes from the spline source.&nbsp;</p>
<p>&nbsp;</p>
<p><strong>Editor Utility Widgets</strong> - The editor utility widget is used to modify the User Interface of the editor. <span>These Widgets are specifically for the Editor UI, and you can use them to create custom Editor tabs. You can then select these custom tabs from the Windows menu, like you would select existing Editor tabs.</span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>