# Code of your exercise

<rule name="TripleNestedIfStatement"
      language="java"
      message="BadlyStructuredCode"
      class="net.sourceforge.pmd.lang.rule.XPathRule">
   <description>
      Rule that flags triple-nested if statements. Also flags
      cases where other constructs are found in between.
   </description>
   <priority>3</priority>
   <properties>
      <property name="version" value="3.1"/>
      <property name="xpath">
         <value>
<![CDATA[
//IfStatement//IfStatement//IfStatement
]]>
         </value>
      </property>
   </properties>
</rule>
