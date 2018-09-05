# Newtonsoft.Json-AOT
A specific Newtonsoft.Json version used for iOS builds. Based on ver 11.0.1 of Newtonsoft.Json.<br/>
<br/>
Includes a Utility.AOTHelper to force AOT type recognition.<br/>
e.g.<br/>
Newtonsoft.Json.Utilities.AotHelper.EnsureType&lt;DataType&gt; ( );<br/>
Newtonsoft.Json.Utilities.AotHelper.EnsureList&lt;DataType&gt; ( );<br/>
<br/>
Also look at https://bytefish.de/blog/enums_json_net/ for examples of custom JsonConverters.
