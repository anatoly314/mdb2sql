# mdb2sql
Tool to export from *.mdb files to sqlite, based on this code https://code.google.com/p/mdb-sqlite/

Few days ago I was need to convert an Access *.mdb database to sqlite and found this tool: https://code.google.com/p/mdb-sqlite/
Unfortunatelly it didn't work flawlessly, it didn't work with encrypted database, hebrew was exported as gibrish, 
exception was thrown while exporting big databases, so I was need to make a few changes:

Replaced sqlite driver by this one: https://bitbucket.org/xerial/sqlite-jdbc
Added Jackcess Encrypt http://jackcessencrypt.sourceforge.net/
and more...

I will continue to improve this little tool to make it totally controlled from command line, btw if you have any suggestion
feel free to ask or submit merge requests.
