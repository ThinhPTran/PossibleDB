
# PossibleDB Server / Clojure Client

<table>
  <tr>
  <td><b>Server  0.1-6</b></td>
  <td><b>Compatible client - possibledb-client 1.6</b></td>
  </tr>
  <tr>
  <!-- server -->
  <td>
    <b>*</b> set proper information in project.clj
    <br />
    <b>*</b> removed unused transit-cljs
    <br />
    <b>*</b> schema support
    <br />
    <b>*</b> fixed get fn - no longer crashes client    
    <br />
    <b>*</b> destroy db support
	<br />
    <b>*</b> spawn db support
	<br />
    <b>*</b> fixed spawn db id issue - id didn't match parent table
	<br />
    <b>*</b> fixed 'delete' reserved word issue
	<br />
  </td>
  <!-- client -->
  <td>    
    <b>*</b> set proper information in project.clj
    <br />
    <b>*</b> schema support
    <br />
    <b>*</b> new destroy-db! fn
    <br />
    <b>*</b> new backup-db! fn
	<br />
    <b>*</b> new spawn-db! fn
	<br />
    <b>*</b> new reset-db! fn
  </td>
  </tr>
</table>
