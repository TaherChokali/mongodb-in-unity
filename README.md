# mongodb-in-unity
<h1>Introduction</h1>
<br/>
.dll Files For Connect And Use MongoDB In Unity
<br/>

<h1>Add Dlls file</h1>
<br/>

<ol>
  <li>Download Zipfile</li>
  <li>Extract Folder</li>
  <li>Import Folder In unity</li>
</ol>
<br/>

<h1>Requirements</h1>
<br/>
<ul>
  <li>Unity 2021.x and after</li>
  <li>.Net 4.7.2</li>
</ul>
  
  
<h1>How To Connect In Unity</h1>
<br/>
### Untyped Documents
```C#
private MongoClient _clientdb;
_clientdb = new MongoClient(_serverData._mongoURI);
```
```C#
using MongoDB.Bson;
using MongoDB.Driver;
```
