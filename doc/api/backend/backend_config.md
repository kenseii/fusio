
# /backend/config


## GET


### GET Response - 200 OK

<div id="psx_model_Collection" class="psx-object"><h4>collection</h4><pre class="psx-object-json"><span class="psx-object-json-pun">{</span>
  <span class="psx-object-json-key">"totalResults"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">Integer</span><span class="psx-object-json-pun">,</span>
  <span class="psx-object-json-key">"startIndex"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">Integer</span><span class="psx-object-json-pun">,</span>
  <span class="psx-object-json-key">"entry"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">Array (Object (<a href="#psx_model_Config" title="RFC4648">config</a>))</span><span class="psx-object-json-pun">,</span>
<span class="psx-object-json-pun">}</span></pre><table class="table psx-object-properties"><colgroup><col width="30%" /><col width="70%" /></colgroup><thead><tr><th>Field</th><th>Description</th></tr></thead><tbody><tr><td><span class="psx-property-name psx-property-optional">totalResults</span></td><td><span class="psx-property-type">Integer</span><br /><div class="psx-property-description"></div></td></tr><tr><td><span class="psx-property-name psx-property-optional">startIndex</span></td><td><span class="psx-property-type">Integer</span><br /><div class="psx-property-description"></div></td></tr><tr><td><span class="psx-property-name psx-property-optional">entry</span></td><td><span class="psx-property-type">Array (Object (<a href="#psx_model_Config" title="RFC4648">config</a>))</span><br /><div class="psx-property-description"></div></td></tr></tbody></table></div>
<div id="psx_model_Config" class="psx-object"><h4>config</h4><pre class="psx-object-json"><span class="psx-object-json-pun">{</span>
  <span class="psx-object-json-key">"id"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">Integer</span><span class="psx-object-json-pun">,</span>
  <span class="psx-object-json-key">"type"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">Integer</span><span class="psx-object-json-pun">,</span>
  <span class="psx-object-json-key">"name"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">String</span><span class="psx-object-json-pun">,</span>
  <span class="psx-object-json-key">"description"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">String</span><span class="psx-object-json-pun">,</span>
  <span class="psx-object-json-key">"value"</span><span class="psx-object-json-pun">: </span><span class="psx-property-type">Mixed</span><span class="psx-object-json-pun">,</span>
<span class="psx-object-json-pun">}</span></pre><table class="table psx-object-properties"><colgroup><col width="30%" /><col width="70%" /></colgroup><thead><tr><th>Field</th><th>Description</th></tr></thead><tbody><tr><td><span class="psx-property-name psx-property-optional">id</span></td><td><span class="psx-property-type">Integer</span><br /><div class="psx-property-description"></div></td></tr><tr><td><span class="psx-property-name psx-property-optional">type</span></td><td><span class="psx-property-type">Integer</span><br /><div class="psx-property-description"></div></td></tr><tr><td><span class="psx-property-name psx-property-optional">name</span></td><td><span class="psx-property-type">String</span><br /><div class="psx-property-description"></div></td></tr><tr><td><span class="psx-property-name psx-property-optional">description</span></td><td><span class="psx-property-type">String</span><br /><div class="psx-property-description"></div></td></tr><tr><td><span class="psx-property-name psx-property-optional">value</span></td><td><span class="psx-property-type">Mixed</span><br /><div class="psx-property-description"></div><dl class="psx-property-constraint"><dt>OneOf</dt><dd><ul class="psx-constraint-oneof"><li>String</li><li>Number</li><li>Boolean</li><li>Null</li></ul></dd></dl></td></tr></tbody></table></div>
