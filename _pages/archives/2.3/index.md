---
layout: default
permalink: "/archives/2.3/index.html"
---

<h1>GeoAPI 2.3 (archived)</h1>

<div class="bg-red-100 border border-red-400 text-red-700 px-4 py-3 my-4 rounded relative" role="alert">
  <strong class="font-bold">Note:</strong>
  <span class="block sm:inline">GeoAPI 2.3 is a legacy milestone. See home page for latest release.</span>
</div>

<p>
  GeoAPI 2.3 was the development branch of <a href="../3.0/index.html">GeoAPI 3.0</a>, which is formalized in
  the <a class="externalLink" href="http://www.opengeospatial.org/standards/geoapi">OGC 09-083</a> document.
  This release required a Java environment Java 5 or higher.
</p>

<h2>Changes in API</h2>

<p>
  The following table gives the links to all changes in the 2.3 series of milestones.
  The cell in the upper-left corner links to the most recent API changes.
  The last column links to the API changes in any milestone since 2.3-M1.
  The changes since 2.3-M1 give the cleanest picture of what actually changed,
  because the changes since the previous version are often &quot;polluted&quot;
  by the methods that are deprecated before to be removed.
</p>

<table style="padding-left: 40px; border-spacing:6px;">
  <tr>
    <td>Changes in <b>M6</b> since:</td>
    <td><a href="../changes/2.3-M6/since-M5.html">M5</a></td>
    <td><a href="../changes/2.3-M6/since-M4.html">M4</a></td>
    <td><a href="../changes/2.3-M6/since-M3.html">M3</a></td>
    <td><a href="../changes/2.3-M6/since-M2.html">M2</a></td>
    <td><a href="../changes/2.3-M6/since-M1.html">M1</a></td>
  </tr><tr>
    <td>Changes in <b>M5</b> since:</td>
    <td></td>
    <td><a href="../changes/2.3-M5/since-M4.html">M4</a></td>
    <td><a href="../changes/2.3-M5/since-M3.html">M3</a></td>
    <td><a href="../changes/2.3-M5/since-M2.html">M2</a></td>
    <td><a href="../changes/2.3-M5/since-M1.html">M1</a></td>
  </tr><tr>
    <td>Changes in <b>M4</b> since:</td>
    <td></td>
    <td></td>
    <td><a href="../changes/2.3-M4/since-M3.html">M3</a></td>
    <td><a href="../changes/2.3-M4/since-M2.html">M2</a></td>
    <td><a href="../changes/2.3-M4/since-M1.html">M1</a></td>
  </tr><tr>
    <td>Changes in <b>M3</b> since:</td>
    <td></td>
    <td></td>
    <td></td>
    <td><a href="../changes/2.3-M3/since-M2.html">M2</a></td>
    <td><a href="../changes/2.3-M3/since-M1.html">M1</a></td>
  </tr><tr>
    <td>Changes in <b>M2</b> since:</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td><a href="../changes/2.3-M2/since-M1.html">M1</a></td>
  </tr>
</table>

<h2>Release notes</h2>

<h3>Version 2.3-M9</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-184">GEO-184</a> - Move Factory and related exception classes to org.opengis.util</li>
</ul>

<h3>Version 2.3-M8</h3>

<ul>
  <li>Minor compatible editions only.</li>
</ul>

<h3>Version 2.3-M7</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-165">GEO-165</a> - Upgrade the JSR-275 dependency. There is no change in GeoAPI interfaces.</li>
</ul>

<h3>Version 2.3-M6</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-187">GEO-187</a> - Typo in metadata method names or annotations. This is completing the fix provided in 2.3-M5 by fixing the case of letters in class names.</li>
</ul>

<h3>Version 2.3-M5</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-187">GEO-187</a> - Typo in metadata method names or annotations</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-72">GEO-072</a> - Proposal for RecordType/Record implementation</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-183">GEO-183</a> - Need to simplify the distribution (geoapi / geoapi-pending / geoapi-dummy-pending)</li>
</ul>

<h3>Version 2.3-M4</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-168">GEO-168</a> - Proposal implementation of the ISO 19115-2</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-174">GEO-174</a> - New ISO 19111:2007 interface: CC_Formula</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-182">GEO-182</a> - OperationMethod.[source|target]Dimensions now optional in latest ISO 19111</li>
</ul>

<h3>Version 2.3-M3</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-175">GEO-175</a> - Remove VerticalDatumType.ELLIPSOIDAL</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-133">GEO-133</a> - ISO 19111 departure in VerticalDatumType.ELLIPSOIDAL</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-167">GEO-167</a> - Move to plurial some getters that returns a collection</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-85">GEO-085</a> - Bearing has angle with no units.</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-156">GEO-156</a> - NPE in org.opengis.feature.IllegalAttributeException.toString()</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-169">GEO-169</a> - Consider making CodeList.valueOf(String) to ignore whitespaces</li>
</ul>

<h3>Version 2.3-M2</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-162">GEO-162</a> - Util: Drop the Clonable interface since it's almost not used.</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-163">GEO-163</a> - Annotation: Drop the Profile annotation and Compliance enum</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-166">GEO-166</a> - Specifying the condition when an attribute is annotated with UML(obligation=CONDITIONAL)</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-171">GEO-171</a> - Move some interfaces from &quot;geoapi&quot; to &quot;geoapi-pending&quot;</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-158">GEO-158</a> - PropertyIsLike option to ignore case</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-161">GEO-161</a> - ISO 19111 departure in CompoundCRS</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-178">GEO-178</a> - IncompatibleOperationException is a checked exception, but not used anywhere</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-170">GEO-170</a> - NameFactory.createNameSpace(...) need to be more extensible</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-176">GEO-176</a> - Javadocs for all CodeLists need to distinguish family() and values()</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-173">GEO-173</a> - Drop org.opengis.referencing.operation.Operation</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-177">GEO-177</a> - Add CoordinateOperationAuthorityFactory.createOperationMethod(String);</li>
</ul>

<h3>Version 2.3-M1</h3>

<ul>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-71">GEO-071</a> - Incorrect implementation of org.opengis.util.GenericName</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-77">GEO-077</a> - Standardized mapping: ISO 19103 to Java/GeoAPI</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-172">GEO-172</a> - New ISO 19111:2007 interface: CS_GeodeticCS</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-54">GEO-054</a> - Add setter methods to metadata interfaces</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-83">GEO-083</a> - Metadata is missing the &quot;application&quot; package</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-145">GEO-145</a> - Make GeneralName easier to understand</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-9">GEO-009</a> - Create a link toward JIRA from the GeoAPI main page</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-42">GEO-042</a> - Publish a table of stable modules and modules in progress</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-74">GEO-074</a> - Consider removing org.opengis.display.go.style package (to be replaced by org.opengis.sld).</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-132">GEO-132</a> - Document better the departure from OGC/ISO specifications</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-140">GEO-140</a> - Add a @pending javadoc annotation to any experimental interface</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-157">GEO-157</a> - Split geoapi in two modules: &quot;geoapi&quot; and &quot;pending&quot;</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-160">GEO-160</a> - Remove packages GO, Layer and clean deprecated sld packages classes</li>
  <li><a class="externalLink" href="https://osgeo-org.atlassian.net/projects/GEO/issues/GEO-164">GEO-164</a> - Create a specification draft for June 2009 OGC meeting (Boston)</li>
</ul>
