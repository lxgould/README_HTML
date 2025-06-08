# README_HTML

<h3>Header 1</h3>
<div style="float: left;">
    <img align="right" src="images/perl_flow_gh_readme.jpg" width="500" />

<p>With the SSIS process, imports of all farms are controlled by a SQL Server scheduled job, <em>pigknowsImport</em>.  That job executes a single stored procedure, <code>PigKnows.EXT.Import</code>.  Within that procedure, the SSIS package,  <code>ImportPigKnows.dtsx</code> is called to copy an archive file (one for each farm) to SPGFS1 and then extract the contents of the archive. Then several other procedures within <code>PigKnows.EXT.Import</code> are called to move the extracted files into the proper tables.</p>
</div>
<div style="clear:both"></div>

<hr>
<h3>Header 2</h3>
<div style="float: left;">

<img align="right" src="images/ssis_flow_gh_readme.jpg" width="500" />

<p>With the SSIS process, imports of all farms are controlled by a SQL Server scheduled job, <em>pigknowsImport</em>.  That job executes a single stored procedure, <code>PigKnows.EXT.Import</code>.  Within that procedure, the SSIS package,  <code>ImportPigKnows.dtsx</code> is called to copy an archive file (one for each farm) to SPGFS1 and then extract the contents of the archive. Then several other procedures within <code>PigKnows.EXT.Import</code> are called to move the extracted files into the proper tables.</p>

</div>
