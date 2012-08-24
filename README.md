Workflow
========

 powershell ./Src/b.ps1 t
 
 for $doc in doc() return xdmp:document-delete(xdmp:node-uri($doc))