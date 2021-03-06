===========================
Sublime Text 2 DITA Goodies
===========================
About
-----
Sublime Text 2 DITA Goodies is set of tools for DITA authoring with Sublime Text 2. It contains snippets and context menu extentions.

`DITA Specification <http://docs.oasis-open.org/dita/v1.2/os/spec/DITA1.2-spec.html>`_

Installation
------------
1. Switch to Sublime Text 2 Packages directory (try Preferences -> Browse Packages);
2. Put ST2-DITA-Goodies directory here.

Snippets
--------
Snippets are shortcuts for peaces of code. Type shortcut + [TAB] and ST2 will replace it with your code. Set of replacings see below.

`More on snippets <http://sublimetext.info/docs/en/extensibility/snippets.html>`_

**topicref**
::

	<topicref href="${1:}" type="${2:}" id="${3:}">
	</topicref>

**concept**
::

	<?xml version="1.0" encoding="UTF-8"?>
	<!DOCTYPE concept PUBLIC "-//OASIS//DTD DITA Concept//EN" "concept.dtd">
	<concept id="${1:id}">
		<title>${2:title}</title>
		<conbody>
			<p>${3:}</p>
		</conbody>
	</concept>

**task**
::

	<?xml version="1.0" encoding="UTF-8"?>
	<!DOCTYPE task PUBLIC "-//OASIS//DTD DITA Task//EN" "task.dtd">
	<task id="${1:id}">
		<title>${2:title}</title>
		<taskbody>
			
		</taskbody>
	</task>

**context**
::

	<context>
	    <p>${1:}</p>
	</context>

**prereq**
::

	<prereq>
	    <p>${1:}</p>
	</prereq>

**steps**
::

	<steps>
	    <step>
	        <cmd>${1:}</cmd>
	    </step>
	</steps>

**stepsu**
::

	<steps-unordered>
		<step>
		    <cmd>${1:}</cmd>
		</step>
	</steps-unordered>

**step**
::

	<step>
	    <cmd>${1:}</cmd>
	</step>


**result**
::

	<result>
		<p>${1:}</p>
	</result>

**related**
::

	<related-links>
	 	<link href="${1:href}">
	 	  	<linktext>${2:linktext}</linktext>
	  	</link>
	</related-links>

**link**
::

	<link href="${1:href}">
	  	<linktext>${2:linktext}</linktext>
	</link>

**table**
::

	<table>
	    <title>${1:}</title>
	    <tgroup cols="${2:}">
	       	<thead>
		       	<row>
		       		<entry>${3:}</entry>
		        </row>
	       	</thead>
	        <tbody>
		        <row>
		        	<entry>${4:}</entry>
		        </row>
		    </tbody>
	    </tgroup>
	</table>

**row**
::

	<row>
		<entry>${1:}</entry>
	</row>

**entry**
::

	<entry>${1:}</entry>

**fig**
::

	<fig>
		<title>${1:title}</title>
		<image href="${2:}" alt="${3:}"/>
	</fig>

**uicontrol**
::

	<uicontrol>${1:}</uicontrol>

**val**
::

	<?xml version="1.0" encoding="UTF-8"?> 
	<val>
	${1:val}
	</val>

**prope**
::

	<prop att="${1:}" val="${2:}" action="exclude"/>

**propf**
::

	<prop action="flag" att="${1:}" val="${2:}" img="${3:}" alt="${4:}"/>

**comm**
::

	<!--${1:}-->

**ol**
::

	<ol>
		<li>${1:}</li>
	</ol>

**ul**
::

	<ul>
		<li>${1:}</li>
	</ul>

**li**
::

	<li>${1:}</li>

**p**
::

	<p>${1:}</p>