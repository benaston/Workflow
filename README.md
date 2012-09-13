Workflow
========

 powershell ./Src/b.ps1 t
 
 for $doc in doc() return xdmp:document-delete(xdmp:node-uri($doc))
 
 xquery version "1.0-ml";

let $d := collection('Preferences')
return $d;