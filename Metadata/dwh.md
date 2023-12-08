<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_CHAaQIUmEe6BKsDnQj9IRA" name="dwh" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_CHN1oIUmEe6BKsDnQj9IRA" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_QjlYkIUmEe6BKsDnQj9IRA" value="CSG1_ORA2"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_QjlYkYUmEe6BKsDnQj9IRA" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_Qjl_oIUmEe6BKsDnQj9IRA" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_Qjl_oYUmEe6BKsDnQj9IRA" value="6F23E4E8A3281AF328EB08370AA8572A"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_Qjl_ooUmEe6BKsDnQj9IRA" value="jdbc:oracle:thin:@195.83.93.26:1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_hZDAsJAlEe69cu6-bNESsg" name="CSG1_ORA2">
    <attribute defType="com.stambia.rdbms.schema.name" id="_hZRDIJAlEe69cu6-bNESsg" value="CSG1_ORA2"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_hZRDIZAlEe69cu6-bNESsg" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_hZRqMJAlEe69cu6-bNESsg" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_hZRqMZAlEe69cu6-bNESsg" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_jzfp-5AlEe69cu6-bNESsg" name="SAS_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_jzfp_JAlEe69cu6-bNESsg" value="SAS_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_jzfp_ZAlEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_j4uvMJAlEe69cu6-bNESsg" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_j4uvMZAlEe69cu6-bNESsg" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j4uvMpAlEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j4uvM5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j4uvNJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j4uvNZAlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j4uvNpAlEe69cu6-bNESsg" name="EMAIL" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_j4uvN5AlEe69cu6-bNESsg" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j4uvOJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j4uvOZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j4uvOpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j4uvO5AlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j4uvPJAlEe69cu6-bNESsg" name="STATUS_EMAIL" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_j4uvPZAlEe69cu6-bNESsg" value="STATUS_EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j4uvPpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j4uvP5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j4uvQJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j4uvQZAlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j4uvQpAlEe69cu6-bNESsg" name="ID_FICHIER" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_j4uvQ5AlEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j4uvRJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j4uvRZAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j4uvRpAlEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j4uvR5AlEe69cu6-bNESsg" name="DATE_IMPORT" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_j4uvSJAlEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j4uvSZAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j4uvSpAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j4uvS5AlEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j4uvTJAlEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_j44gMJAlEe69cu6-bNESsg" name="PK_CLE_CLIENT2">
        <node defType="com.stambia.rdbms.colref" id="_j44gMZAlEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_j44gMpAlEe69cu6-bNESsg" ref="resource.md#_j4uvMJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_uoE74JAnEe69cu6-bNESsg" name="FK_ID_FICHIER2">
        <node defType="com.stambia.rdbms.relation" id="_uoE74ZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_uoE74pAnEe69cu6-bNESsg" ref="resource.md#_j4uvQpAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_uoE745AnEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_uoFi8JAnEe69cu6-bNESsg" name="FK_CLE_CLIENT2">
        <node defType="com.stambia.rdbms.relation" id="_uoFi8ZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_uoFi8pAnEe69cu6-bNESsg" ref="resource.md#_j4uvMJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_uoFi85AnEe69cu6-bNESsg" ref="resource.md#_jlQZkJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_ohz5gZAtEe69cu6-bNESsg" name="REJET_EMAIL">
        <attribute defType="com.stambia.rdbms.check.sql" id="_wK3VkJAtEe69cu6-bNESsg" value="EMAIL like '%@%.%'"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_YU4icJAuEe69cu6-bNESsg" value="200"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_0wYTjZWkEe6KJ9B1NiSMNg" name="ACT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_0wYTjpWkEe6KJ9B1NiSMNg" value="ACT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_0wYTj5WkEe6KJ9B1NiSMNg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_0wYTkJWkEe6KJ9B1NiSMNg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_0wYTkZWkEe6KJ9B1NiSMNg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_0wYTkpWkEe6KJ9B1NiSMNg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_QKydUZWpEe6KJ9B1NiSMNg" name="Status">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_doxscJWpEe6KJ9B1NiSMNg" value="status obligatoire"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_f10y0JWpEe6KJ9B1NiSMNg" value="STATUS_EMAIL is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_YI-xAZWrEe6KJ9B1NiSMNg" name="action">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_ZmIrgJWrEe6KJ9B1NiSMNg" value="ACT  = 'S' or  ACT = 'M' or ACT = 'C'"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_amvM4JWrEe6KJ9B1NiSMNg" value="ACT  is not null"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_jua8pJAlEe69cu6-bNESsg" name="SAS_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_jua8pZAlEe69cu6-bNESsg" value="SAS_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_jua8ppAlEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_jzZjQJAlEe69cu6-bNESsg" name="CLE_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_jzZjQZAlEe69cu6-bNESsg" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jzZjQpAlEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jzZjQ5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jzZjRJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jzZjRZAlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jzZjRpAlEe69cu6-bNESsg" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_jzZjR5AlEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jzZjSJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jzZjSZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jzZjSpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jzZjS5AlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jzfp4JAlEe69cu6-bNESsg" name="TYPE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_jzfp4ZAlEe69cu6-bNESsg" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jzfp4pAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jzfp45AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jzfp5JAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jzfp5ZAlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jzfp5pAlEe69cu6-bNESsg" name="CABINET_RATTACHEMENT" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_jzfp55AlEe69cu6-bNESsg" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jzfp6JAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jzfp6ZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jzfp6pAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jzfp65AlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jzfp7JAlEe69cu6-bNESsg" name="ID_FICHIER" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_jzfp7ZAlEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jzfp7pAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jzfp75AlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jzfp8JAlEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jzfp8ZAlEe69cu6-bNESsg" name="DATE_IMPORT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_jzfp8pAlEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jzfp85AlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jzfp9JAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jzfp9ZAlEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jzfp9pAlEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_jzfp95AlEe69cu6-bNESsg" name="PK_CLE_COMPTE">
        <node defType="com.stambia.rdbms.colref" id="_jzfp-JAlEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_jzfp-ZAlEe69cu6-bNESsg" ref="resource.md#_jzZjQJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_unDBIJAnEe69cu6-bNESsg" name="FK_ID_FICHIER">
        <node defType="com.stambia.rdbms.relation" id="_unDBIZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_unDBIpAnEe69cu6-bNESsg" ref="resource.md#_jzfp7JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_unDBI5AnEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.check" id="_HYwoAZWeEe6KJ9B1NiSMNg" name="Type_ligne">
        <attribute defType="com.stambia.rdbms.check.sql" id="_gQ93sJWeEe6KJ9B1NiSMNg" value="TYPE is not null"/>
        <attribute defType="com.stambia.rdbms.check.severity" id="_jZV94JWeEe6KJ9B1NiSMNg" value="200"/>
        <attribute defType="com.stambia.rdbms.check.remarks" id="_mizCIJWeEe6KJ9B1NiSMNg" value="type_ligne présent&#xD;&#xA;"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_ANOHAZWhEe6KJ9B1NiSMNg" name="Status">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_E-xxgJWhEe6KJ9B1NiSMNg" value="status est présent et égale à 0 ou 1"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_LgB4AJWhEe6KJ9B1NiSMNg" value="STATUS is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_Oiyo8ZWiEe6KJ9B1NiSMNg" name="cabinet">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_QC6X4JWiEe6KJ9B1NiSMNg" value="Le cabinet de rattachement appartient à une liste prédéfinie"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_TfcJIJWiEe6KJ9B1NiSMNg" value="CABINET_RATTACHEMENT in ( 'Lille', 'Roubaix', 'Tourcoing' , 'Dunkerque', 'Villeneuve d''ascq', 'Douai', 'Wattrelos', 'Valenciennes', 'Marcq en Baroeul' )"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_0kIAQ5WkEe6KJ9B1NiSMNg" name="ACT" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_0kIARJWkEe6KJ9B1NiSMNg" value="ACT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_0kIARZWkEe6KJ9B1NiSMNg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_0kIARpWkEe6KJ9B1NiSMNg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_0kIAR5WkEe6KJ9B1NiSMNg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_0kIASJWkEe6KJ9B1NiSMNg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_pxR2sZWmEe6KJ9B1NiSMNg" name="Action">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_tu3GkJWmEe6KJ9B1NiSMNg" value="ACT = 'S' ou 'M' ou 'C'"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_wrdakJWmEe6KJ9B1NiSMNg" value="ACT is not null"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_jo7_sZAlEe69cu6-bNESsg" name="SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_jo7_spAlEe69cu6-bNESsg" value="SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_jo7_s5AlEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_juUO8JAlEe69cu6-bNESsg" name="ID_FICHIER" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_juUO8ZAlEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_juUO8pAlEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_juUO85AlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_juUO9JAlEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_juUO9ZAlEe69cu6-bNESsg" name="NOM_FICHIER" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_juUO9pAlEe69cu6-bNESsg" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_juUO95AlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_juUO-JAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_juUO-ZAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_juUO-pAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_juUO-5AlEe69cu6-bNESsg" name="DATE_IMPORT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_juUO_JAlEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_juUO_ZAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_juUO_pAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_juUO_5AlEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_juUPAJAlEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_jua8oJAlEe69cu6-bNESsg" name="PK_ID_FICHIER">
        <node defType="com.stambia.rdbms.colref" id="_jua8oZAlEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_jua8opAlEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_jlWgP5AlEe69cu6-bNESsg" name="TRANSCO">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_jlWgQJAlEe69cu6-bNESsg" value="TRANSCO"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_jlWgQZAlEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_jo15EJAlEe69cu6-bNESsg" name="TYPE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_jo15EZAlEe69cu6-bNESsg" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jo15EpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jo15E5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jo15FJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jo15FZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jo15FpAlEe69cu6-bNESsg" name="CODE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_jo15F5AlEe69cu6-bNESsg" value="CODE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jo15GJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jo15GZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jo15GpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jo15G5AlEe69cu6-bNESsg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jo15HJAlEe69cu6-bNESsg" name="LIBELLE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_jo15HZAlEe69cu6-bNESsg" value="LIBELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jo15HpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jo15H5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jo15IJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jo15IZAlEe69cu6-bNESsg" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_j8Wq8ZAlEe69cu6-bNESsg" name="SAS_TEL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_j8Wq8pAlEe69cu6-bNESsg" value="SAS_TEL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_j8Wq85AlEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_kBiF4JAlEe69cu6-bNESsg" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_kBiF4ZAlEe69cu6-bNESsg" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kBiF4pAlEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kBiF45AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kBiF5JAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kBiF5ZAlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kBiF5pAlEe69cu6-bNESsg" name="PHONE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_kBiF55AlEe69cu6-bNESsg" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kBiF6JAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kBiF6ZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kBiF6pAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kBiF65AlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kBiF7JAlEe69cu6-bNESsg" name="STATUS_TELEPHONE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_kBiF7ZAlEe69cu6-bNESsg" value="STATUS_TELEPHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kBiF7pAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kBiF75AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kBiF8JAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kBiF8ZAlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kBr24JAlEe69cu6-bNESsg" name="FAVORI" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_kBr24ZAlEe69cu6-bNESsg" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kBr24pAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kBr245AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kBr25JAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kBr25ZAlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kBr25pAlEe69cu6-bNESsg" name="TYPE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_kBr255AlEe69cu6-bNESsg" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kBr26JAlEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kBr26ZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kBr26pAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kBr265AlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kBr27JAlEe69cu6-bNESsg" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_kBr27ZAlEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kBr27pAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kBr275AlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kBr28JAlEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kBr28ZAlEe69cu6-bNESsg" name="DATE_IMPORT" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_kBr28pAlEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kBr285AlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kBr29JAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kBr29ZAlEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kBr29pAlEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_kBr295AlEe69cu6-bNESsg" name="PK_CLE_CLIENT4">
        <node defType="com.stambia.rdbms.colref" id="_kBr2-JAlEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_kBr2-ZAlEe69cu6-bNESsg" ref="resource.md#_kBiF4JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_kBr2-pAlEe69cu6-bNESsg" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_kBr2-5AlEe69cu6-bNESsg" ref="resource.md#_kBr25pAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=TYPE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_uovqQJAnEe69cu6-bNESsg" name="FK_ID_FICHIER4">
        <node defType="com.stambia.rdbms.relation" id="_uovqQZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_uovqQpAnEe69cu6-bNESsg" ref="resource.md#_kBr27JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_uovqQ5AnEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_uovqRJAnEe69cu6-bNESsg" name="FK_CLE_CLIENT4">
        <node defType="com.stambia.rdbms.relation" id="_uovqRZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_uovqRpAnEe69cu6-bNESsg" ref="resource.md#_kBiF4JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_uovqR5AnEe69cu6-bNESsg" ref="resource.md#_jlQZkJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_019XKZWkEe6KJ9B1NiSMNg" name="ACT" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_019XKpWkEe6KJ9B1NiSMNg" value="ACT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_019XK5WkEe6KJ9B1NiSMNg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_019XLJWkEe6KJ9B1NiSMNg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_019XLZWkEe6KJ9B1NiSMNg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_019XLpWkEe6KJ9B1NiSMNg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_IvDZoZWrEe6KJ9B1NiSMNg" name="ACTION">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_Lw2WsJWrEe6KJ9B1NiSMNg" value="ACT  = 'S' or  ACT = 'M' or ACT = 'C'"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_M4absJWrEe6KJ9B1NiSMNg" value="ACT is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_e4jnYZWrEe6KJ9B1NiSMNg" name="telephone renseigne">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_V5j2oJWsEe6KJ9B1NiSMNg" value="PHONE is not null"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_XA4rEJWsEe6KJ9B1NiSMNg" value="PHONE is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_jK3KEZWrEe6KJ9B1NiSMNg" name="status">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_royYoJWrEe6KJ9B1NiSMNg" value="Statut du n° de téléphone = Téléphone inactif ou Téléphone actif ou Téléphone NPAI&#xD;&#xA;"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_sh81QJWrEe6KJ9B1NiSMNg" value="STATUS_TELEPHONE is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_3iOr0ZWrEe6KJ9B1NiSMNg" name="favori">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_5ejOkJWrEe6KJ9B1NiSMNg" value="FAVORI = 'Oui' or FAVORI = 'Non'"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_8KGO0JWrEe6KJ9B1NiSMNg" value="FAVORI is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_9fIvIZWrEe6KJ9B1NiSMNg" name="type telephone">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_CB7k4JWsEe6KJ9B1NiSMNg" value="TYPE = 'Fixe' or TYPE = 'Portable'"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_FHF_AJWsEe6KJ9B1NiSMNg" value="TYPE is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_bSLhIZWsEe6KJ9B1NiSMNg" name="format telephone">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_cmRmQJWsEe6KJ9B1NiSMNg" value="numero de telephone doit respecter le format xx.xx.xx.xx.xx"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_epVDIJWsEe6KJ9B1NiSMNg" value="PHONE LIKE '__.__.__.__.__'"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_jfbeYZAlEe69cu6-bNESsg" name="SAS_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_jfbeYpAlEe69cu6-bNESsg" value="SAS_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_jfbeY5AlEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_jlQZkJAlEe69cu6-bNESsg" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZkZAlEe69cu6-bNESsg" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZkpAlEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZk5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZlJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZlZAlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZlpAlEe69cu6-bNESsg" name="CLE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZl5AlEe69cu6-bNESsg" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZmJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZmZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZmpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZm5AlEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZnJAlEe69cu6-bNESsg" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZnZAlEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZnpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZn5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZoJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZoZAlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZopAlEe69cu6-bNESsg" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZo5AlEe69cu6-bNESsg" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZpJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZpZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZppAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZp5AlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZqJAlEe69cu6-bNESsg" name="CIVILITE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZqZAlEe69cu6-bNESsg" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZqpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZq5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZrJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZrZAlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZrpAlEe69cu6-bNESsg" name="PRENOM" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZr5AlEe69cu6-bNESsg" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZsJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZsZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZspAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZs5AlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZtJAlEe69cu6-bNESsg" name="NOM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZtZAlEe69cu6-bNESsg" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZtpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZt5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZuJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZuZAlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZupAlEe69cu6-bNESsg" name="DATE_ANNIVERSAIRE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZu5AlEe69cu6-bNESsg" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZvJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZvZAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZvpAlEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZv5AlEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZwJAlEe69cu6-bNESsg" name="SEXE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZwZAlEe69cu6-bNESsg" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZwpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZw5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZxJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZxZAlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlQZxpAlEe69cu6-bNESsg" name="MUTUELLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlQZx5AlEe69cu6-bNESsg" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlQZyJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlQZyZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlQZypAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlQZy5AlEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlWgMJAlEe69cu6-bNESsg" name="ID_FICHIER" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlWgMZAlEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlWgMpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlWgM5AlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlWgNJAlEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_jlWgNZAlEe69cu6-bNESsg" name="DATE_IMPORT" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_jlWgNpAlEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_jlWgN5AlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_jlWgOJAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_jlWgOZAlEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_jlWgOpAlEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_jlWgO5AlEe69cu6-bNESsg" name="PK_CLE_CLIENT">
        <node defType="com.stambia.rdbms.colref" id="_jlWgPJAlEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_jlWgPZAlEe69cu6-bNESsg" ref="resource.md#_jlQZkJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_umWdkJAnEe69cu6-bNESsg" name="FK_CLE_COMPTE">
        <node defType="com.stambia.rdbms.relation" id="_umWdkZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_umWdkpAnEe69cu6-bNESsg" ref="resource.md#_jlQZlpAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_umWdk5AnEe69cu6-bNESsg" ref="resource.md#_jzZjQJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_umXEoJAnEe69cu6-bNESsg" name="FK_ID_FICHIER1">
        <node defType="com.stambia.rdbms.relation" id="_umXEoZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_umXEopAnEe69cu6-bNESsg" ref="resource.md#_jlWgMJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_umXEo5AnEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_0e0Cl5WkEe6KJ9B1NiSMNg" name="ACT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_0e0CmJWkEe6KJ9B1NiSMNg" value="ACT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_0e0CmZWkEe6KJ9B1NiSMNg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_0e0CmpWkEe6KJ9B1NiSMNg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_0e0Cm5WkEe6KJ9B1NiSMNg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_0e0CnJWkEe6KJ9B1NiSMNg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_aqcvkZWoEe6KJ9B1NiSMNg" name="type_ligne">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_fe9ncJWoEe6KJ9B1NiSMNg" value="TYPE n'est pas vide"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_gpI7kJWoEe6KJ9B1NiSMNg" value="TYPE is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_mzWbEZWoEe6KJ9B1NiSMNg" name="ACTION">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_pH3bYJWoEe6KJ9B1NiSMNg" value="ACT  = 'S' or  ACT = 'M' or ACT = 'C'"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_rMio4JWoEe6KJ9B1NiSMNg" value="ACT is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_zaW-4ZWoEe6KJ9B1NiSMNg" name="STATUS">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_0_2WAJWoEe6KJ9B1NiSMNg" value="STATUS est présent&#xD;&#xA;"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_2_fSgJWoEe6KJ9B1NiSMNg" value="STATUS is not null"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_j44gNJAlEe69cu6-bNESsg" name="SAS_FILESRC">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_j44gNZAlEe69cu6-bNESsg" value="SAS_FILESRC"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_j44gNpAlEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_j8QkUJAlEe69cu6-bNESsg" name="FILE_NOM" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkUZAlEe69cu6-bNESsg" value="FILE_NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkUpAlEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkU5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkVJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkVZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkVpAlEe69cu6-bNESsg" name="F1" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkV5AlEe69cu6-bNESsg" value="F1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkWJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkWZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkWpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkW5AlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkXJAlEe69cu6-bNESsg" name="F2" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkXZAlEe69cu6-bNESsg" value="F2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkXpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkX5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkYJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkYZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkYpAlEe69cu6-bNESsg" name="F3" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkY5AlEe69cu6-bNESsg" value="F3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkZJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkZZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkZpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkZ5AlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkaJAlEe69cu6-bNESsg" name="F4" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkaZAlEe69cu6-bNESsg" value="F4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkapAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8Qka5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkbJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkbZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkbpAlEe69cu6-bNESsg" name="F5" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8Qkb5AlEe69cu6-bNESsg" value="F5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkcJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkcZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkcpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8Qkc5AlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkdJAlEe69cu6-bNESsg" name="F6" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkdZAlEe69cu6-bNESsg" value="F6"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkdpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8Qkd5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkeJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkeZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkepAlEe69cu6-bNESsg" name="F7" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8Qke5AlEe69cu6-bNESsg" value="F7"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkfJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkfZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkfpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8Qkf5AlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkgJAlEe69cu6-bNESsg" name="F8" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkgZAlEe69cu6-bNESsg" value="F8"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkgpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8Qkg5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkhJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkhZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkhpAlEe69cu6-bNESsg" name="F9" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8Qkh5AlEe69cu6-bNESsg" value="F9"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkiJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkiZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkipAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8Qki5AlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkjJAlEe69cu6-bNESsg" name="F10" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkjZAlEe69cu6-bNESsg" value="F10"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkjpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8Qkj5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkkJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkkZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkkpAlEe69cu6-bNESsg" name="F11" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8Qkk5AlEe69cu6-bNESsg" value="F11"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QklJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QklZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QklpAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8Qkl5AlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkmJAlEe69cu6-bNESsg" name="F12" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkmZAlEe69cu6-bNESsg" value="F12"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkmpAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8Qkm5AlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QknJAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QknZAlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QknpAlEe69cu6-bNESsg" name="F13" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8Qkn5AlEe69cu6-bNESsg" value="F13"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkoJAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkoZAlEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkopAlEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8Qko5AlEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_j8QkpJAlEe69cu6-bNESsg" name="DATE_IMPORT" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_j8QkpZAlEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_j8QkppAlEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_j8Qkp5AlEe69cu6-bNESsg" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_j8QkqJAlEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_j8QkqZAlEe69cu6-bNESsg" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_j8QkqpAlEe69cu6-bNESsg" value="11"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_uRfA0ZAnEe69cu6-bNESsg" name="SAS_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_uRfA0pAnEe69cu6-bNESsg" value="SAS_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_uRfA05AnEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_uW0MwJAnEe69cu6-bNESsg" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW0MwZAnEe69cu6-bNESsg" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW0MwpAnEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW0Mw5AnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW0MxJAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW0MxZAnEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW0MxpAnEe69cu6-bNESsg" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW0Mx5AnEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW0MyJAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW0MyZAnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW0MypAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW0My5AnEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW0MzJAnEe69cu6-bNESsg" name="LIGNE_1" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW0MzZAnEe69cu6-bNESsg" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW0MzpAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW0Mz5AnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW0M0JAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW0M0ZAnEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW0z0JAnEe69cu6-bNESsg" name="LIGNE_2" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW0z0ZAnEe69cu6-bNESsg" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW0z0pAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW0z05AnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW0z1JAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW0z1ZAnEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW0z1pAnEe69cu6-bNESsg" name="LIGNE_3" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW0z15AnEe69cu6-bNESsg" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW0z2JAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW0z2ZAnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW0z2pAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW0z25AnEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW0z3JAnEe69cu6-bNESsg" name="LIGNE_4" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW0z3ZAnEe69cu6-bNESsg" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW0z3pAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW0z35AnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW0z4JAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW0z4ZAnEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW1a4JAnEe69cu6-bNESsg" name="LIGNE_5" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW1a4ZAnEe69cu6-bNESsg" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW1a4pAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW1a45AnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW1a5JAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW1a5ZAnEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW1a5pAnEe69cu6-bNESsg" name="VILLE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW1a55AnEe69cu6-bNESsg" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW1a6JAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW1a6ZAnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW1a6pAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW1a65AnEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW1a7JAnEe69cu6-bNESsg" name="CODE_POSTAL" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW1a7ZAnEe69cu6-bNESsg" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW1a7pAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW1a75AnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW1a8JAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW1a8ZAnEe69cu6-bNESsg" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW1a8pAnEe69cu6-bNESsg" name="PAYS" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW1a85AnEe69cu6-bNESsg" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW1a9JAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW1a9ZAnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW1a9pAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW1a95AnEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW2B8JAnEe69cu6-bNESsg" name="QUALITE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW2B8ZAnEe69cu6-bNESsg" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW2B8pAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW2B85AnEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW2B9JAnEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW2B9ZAnEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW2B9pAnEe69cu6-bNESsg" name="ID_FICHIER" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW2B95AnEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW2B-JAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW2B-ZAnEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW2B-pAnEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_uW2B-5AnEe69cu6-bNESsg" name="DATE_IMPORT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_uW2B_JAnEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_uW2B_ZAnEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_uW2B_pAnEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_uW2B_5AnEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_uW2CAJAnEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_uW66cJAnEe69cu6-bNESsg" name="PK_CLE_CLIENT3">
        <node defType="com.stambia.rdbms.colref" id="_uW66cZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_uW66cpAnEe69cu6-bNESsg" ref="resource.md#_uW0MwJAnEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_unjXcJAnEe69cu6-bNESsg" name="FK_ID_FICHIER3">
        <node defType="com.stambia.rdbms.relation" id="_unjXcZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_unjXcpAnEe69cu6-bNESsg" ref="resource.md#_uW2B9pAnEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_unjXc5AnEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_unj-gJAnEe69cu6-bNESsg" name="FK_CLE_CLIENT3">
        <node defType="com.stambia.rdbms.relation" id="_unj-gZAnEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_unj-gpAnEe69cu6-bNESsg" ref="resource.md#_uW0MwJAnEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_unj-g5AnEe69cu6-bNESsg" ref="resource.md#_jlQZkJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_0qGsVpWkEe6KJ9B1NiSMNg" name="ACT" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_0qGsV5WkEe6KJ9B1NiSMNg" value="ACT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_0qGsWJWkEe6KJ9B1NiSMNg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_0qGsWZWkEe6KJ9B1NiSMNg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_0qGsWpWkEe6KJ9B1NiSMNg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_0qGsW5WkEe6KJ9B1NiSMNg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_KbHvUZWqEe6KJ9B1NiSMNg" name="ACTION">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_PosncJWqEe6KJ9B1NiSMNg" value="ACT  = 'S' or  ACT = 'M' or ACT = 'C'"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_RLxjwJWqEe6KJ9B1NiSMNg" value="ACT is not null"/>
      </node>
      <node defType="com.stambia.rdbms.check" id="_SiJg0ZWqEe6KJ9B1NiSMNg" name="STATUS">
        <attribute defType="com.stambia.rdbms.check.remarks" id="_WhS28JWqEe6KJ9B1NiSMNg" value="STATUS = suspendu, active, npai"/>
        <attribute defType="com.stambia.rdbms.check.sql" id="_0dhaIJWqEe6KJ9B1NiSMNg" value="STATUS is not null"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_kY7_oZAtEe69cu6-bNESsg" name="DWH_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_kY7_opAtEe69cu6-bNESsg" value="DWH_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_kY7_o5AtEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_keTAwJAtEe69cu6-bNESsg" name="SID_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_keTAwZAtEe69cu6-bNESsg" value="SID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keTAwpAtEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keTAw5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keTAxJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keTn0JAtEe69cu6-bNESsg" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_keTn0ZAtEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keTn0pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keTn05AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keTn1JAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keTn1ZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keTn1pAtEe69cu6-bNESsg" name="LIGNE_1" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_keTn15AtEe69cu6-bNESsg" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keTn2JAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keTn2ZAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keTn2pAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keTn25AtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keTn3JAtEe69cu6-bNESsg" name="LIGNE_2" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_keTn3ZAtEe69cu6-bNESsg" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keTn3pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keTn35AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keTn4JAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keTn4ZAtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keUO4JAtEe69cu6-bNESsg" name="LIGNE_3" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_keUO4ZAtEe69cu6-bNESsg" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keUO4pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keUO45AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keUO5JAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keUO5ZAtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keUO5pAtEe69cu6-bNESsg" name="LIGNE_4" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_keUO55AtEe69cu6-bNESsg" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keUO6JAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keUO6ZAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keUO6pAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keUO65AtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keUO7JAtEe69cu6-bNESsg" name="LIGNE_5" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_keUO7ZAtEe69cu6-bNESsg" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keUO7pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keUO75AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keUO8JAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keUO8ZAtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keU18JAtEe69cu6-bNESsg" name="VILLE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_keU18ZAtEe69cu6-bNESsg" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keU18pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keU185AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keU19JAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keU19ZAtEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keU19pAtEe69cu6-bNESsg" name="CODE_POSTAL" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_keU195AtEe69cu6-bNESsg" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keU1-JAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keU1-ZAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keU1-pAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keU1-5AtEe69cu6-bNESsg" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keU1_JAtEe69cu6-bNESsg" name="PAYS" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_keU1_ZAtEe69cu6-bNESsg" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keU1_pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keU1_5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keU2AJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keU2AZAtEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keU2ApAtEe69cu6-bNESsg" name="QUALITE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_keU2A5AtEe69cu6-bNESsg" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keU2BJAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keU2BZAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keU2BpAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keU2B5AtEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keVdAJAtEe69cu6-bNESsg" name="ID_FICHIER" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_keVdAZAtEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keVdApAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keVdA5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keVdBJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keVdBZAtEe69cu6-bNESsg" name="DATE_IMPORT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_keVdBpAtEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keVdB5AtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keVdCJAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keVdCZAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keVdCpAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_keVdC5AtEe69cu6-bNESsg" name="DATE_MAJ" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_keVdDJAtEe69cu6-bNESsg" value="DATE_MAJ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_keVdDZAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_keVdDpAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_keVdD5AtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_keVdEJAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_keaVgJAtEe69cu6-bNESsg" name="PK_SID_CLIENT2_DWH">
        <node defType="com.stambia.rdbms.colref" id="_keaVgZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_keaVgpAtEe69cu6-bNESsg" ref="resource.md#_keTAwJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kq6gcJAtEe69cu6-bNESsg" name="FK_SID_CLIENT2_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kq6gcZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kq6gcpAtEe69cu6-bNESsg" ref="resource.md#_keTAwJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kq6gc5AtEe69cu6-bNESsg" ref="resource.md#_kpK0AJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kq7HgJAtEe69cu6-bNESsg" name="FK_ID_FICHIER2_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kq7HgZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kq7HgpAtEe69cu6-bNESsg" ref="resource.md#_keVdAJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kq7Hg5AtEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_kecxwZAtEe69cu6-bNESsg" name="DWH_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_kecxwpAtEe69cu6-bNESsg" value="DWH_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_kecxw5AtEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_kjtFMJAtEe69cu6-bNESsg" name="SID_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_kjtsQJAtEe69cu6-bNESsg" value="SID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kjtsQZAtEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kjtsQpAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kjtsQ5AtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kjuTUJAtEe69cu6-bNESsg" name="EMAIL" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_kjuTUZAtEe69cu6-bNESsg" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kjuTUpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kjuTU5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kjuTVJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kjuTVZAtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kju6YJAtEe69cu6-bNESsg" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_kju6YZAtEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kju6YpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kju6Y5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kju6ZJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kju6ZZAtEe69cu6-bNESsg" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kjwIgJAtEe69cu6-bNESsg" name="ID_FICHIER" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_kjwIgZAtEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kjwIgpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kjwIg5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kjwIhJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kjwIhZAtEe69cu6-bNESsg" name="DATE_IMPORT" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_kjwIhpAtEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kjwIh5AtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kjwIiJAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kjwIiZAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kjwIipAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kjwvkJAtEe69cu6-bNESsg" name="DATE_MAJ" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_kjwvkZAtEe69cu6-bNESsg" value="DATE_MAJ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kjwvkpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kjwvk5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kjwvlJAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kjwvlZAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_kj0Z8JAtEe69cu6-bNESsg" name="PK_SID_CLIENT1_DWH">
        <node defType="com.stambia.rdbms.colref" id="_kj0Z8ZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_kj0Z8pAtEe69cu6-bNESsg" ref="resource.md#_kjtFMJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kra2wJAtEe69cu6-bNESsg" name="FK_SID_CLIENT1_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kra2wZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kra2wpAtEe69cu6-bNESsg" ref="resource.md#_kjtFMJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kra2w5AtEe69cu6-bNESsg" ref="resource.md#_kpK0AJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_krbd0JAtEe69cu6-bNESsg" name="FK_ID_FICHIER1_DWH">
        <node defType="com.stambia.rdbms.relation" id="_krbd0ZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_krbd0pAtEe69cu6-bNESsg" ref="resource.md#_kjwIgJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_krbd05AtEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_kj22MZAtEe69cu6-bNESsg" name="DWH_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_kj22MpAtEe69cu6-bNESsg" value="DWH_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_kj22M5AtEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_kpK0AJAtEe69cu6-bNESsg" name="SID_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpK0AZAtEe69cu6-bNESsg" value="SID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpK0ApAtEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpK0A5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpK0BJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpK0BZAtEe69cu6-bNESsg" name="CLE_CLIENT" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpK0BpAtEe69cu6-bNESsg" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpK0B5AtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpK0CJAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpK0CZAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpK0CpAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpLbEJAtEe69cu6-bNESsg" name="SID_COMPTE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpLbEZAtEe69cu6-bNESsg" value="SID_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpLbEpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpLbE5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpLbFJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpLbFZAtEe69cu6-bNESsg" name="STATUS" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpLbFpAtEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpLbF5AtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpLbGJAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpLbGZAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpLbGpAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpLbG5AtEe69cu6-bNESsg" name="TYPE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpLbHJAtEe69cu6-bNESsg" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpLbHZAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpLbHpAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpLbH5AtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpLbIJAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpMCIJAtEe69cu6-bNESsg" name="CIVILITE" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpMCIZAtEe69cu6-bNESsg" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpMCIpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpMCI5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpMCJJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpMCJZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpMCJpAtEe69cu6-bNESsg" name="PRENOM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpMCJ5AtEe69cu6-bNESsg" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpMCKJAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpMCKZAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpMCKpAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpMCK5AtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpMCLJAtEe69cu6-bNESsg" name="NOM" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpMCLZAtEe69cu6-bNESsg" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpMCLpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpMCL5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpMCMJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpMCMZAtEe69cu6-bNESsg" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpMCMpAtEe69cu6-bNESsg" name="DATE_ANNIVERSAIRE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpMCM5AtEe69cu6-bNESsg" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpMCNJAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpMCNZAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpMCNpAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpMCN5AtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpMpMJAtEe69cu6-bNESsg" name="SEXE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpMpMZAtEe69cu6-bNESsg" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpMpMpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpMpM5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpMpNJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpMpNZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpMpNpAtEe69cu6-bNESsg" name="MUTUELLE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpMpN5AtEe69cu6-bNESsg" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpMpOJAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_kpMpOZAtEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpMpOpAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpMpO5AtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpMpPJAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpMpPZAtEe69cu6-bNESsg" name="ID_FICHIER" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpMpPpAtEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpMpP5AtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpMpQJAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpMpQZAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpNQQJAtEe69cu6-bNESsg" name="DATE_IMPORT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpNQQZAtEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpNQQpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpNQQ5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpNQRJAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpNQRZAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kpNQRpAtEe69cu6-bNESsg" name="DATE_MAJ" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_kpNQR5AtEe69cu6-bNESsg" value="DATE_MAJ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kpNQSJAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kpNQSZAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kpNQSpAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kpNQS5AtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_kpQ6oJAtEe69cu6-bNESsg" name="PK_SID_CLIENT">
        <node defType="com.stambia.rdbms.colref" id="_kpQ6oZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_kpQ6opAtEe69cu6-bNESsg" ref="resource.md#_kpK0AJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kr-QYJAtEe69cu6-bNESsg" name="FK_SID_COMPTE_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kr-QYZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kr-QYpAtEe69cu6-bNESsg" ref="resource.md#_kpLbEJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kr-QY5AtEe69cu6-bNESsg" ref="resource.md#_kSn8QJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kr-QZJAtEe69cu6-bNESsg" name="FK_ID_FICHIER0_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kr-QZZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kr-QZpAtEe69cu6-bNESsg" ref="resource.md#_kpMpPZAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kr-QZ5AtEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kr-3cJAtEe69cu6-bNESsg" name="FK_CLE_CLIENT_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kr-3cZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kr-3cpAtEe69cu6-bNESsg" ref="resource.md#_kpK0BZAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kr-3c5AtEe69cu6-bNESsg" ref="resource.md#_jlQZkJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_kNAccZAtEe69cu6-bNESsg" name="DWH_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_kNAccpAtEe69cu6-bNESsg" value="DWH_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_kNAcc5AtEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_kSn8QJAtEe69cu6-bNESsg" name="SID_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_kSn8QZAtEe69cu6-bNESsg" value="SID_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kSn8QpAtEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kSn8Q5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kSn8RJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kSpKYJAtEe69cu6-bNESsg" name="CLE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_kSpKYZAtEe69cu6-bNESsg" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kSpKYpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kSpKY5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kSpKZJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kSpKZZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kSpxcJAtEe69cu6-bNESsg" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_kSpxcZAtEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kSpxcpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kSpxc5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kSpxdJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kSpxdZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kSqYgJAtEe69cu6-bNESsg" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_kSqYgZAtEe69cu6-bNESsg" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kSqYgpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kSqYg5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kSqYhJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kSq_kJAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kSrmoJAtEe69cu6-bNESsg" name="CABINET_RATTACHEMENT" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_kSrmoZAtEe69cu6-bNESsg" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kSrmopAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kSrmo5AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kSrmpJAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kSrmpZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kSsNsJAtEe69cu6-bNESsg" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_kSsNsZAtEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kSsNspAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kSsNs5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kSsNtJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kSs0wJAtEe69cu6-bNESsg" name="DATE_IMPORT" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_kSs0wZAtEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kSs0wpAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kSs0w5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kSs0xJAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kSs0xZAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kStb0JAtEe69cu6-bNESsg" name="DATE_MAJ" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_kStb0ZAtEe69cu6-bNESsg" value="DATE_MAJ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kStb0pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kStb05AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kStb1JAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kStb1ZAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_kSyUUJAtEe69cu6-bNESsg" name="PK_SID_COMPTE_DWH">
        <node defType="com.stambia.rdbms.colref" id="_kSyUUZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_kSyUUpAtEe69cu6-bNESsg" ref="resource.md#_kSn8QJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kp2wgJAtEe69cu6-bNESsg" name="FK_CLE_COMPTE_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kp2wgZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kp2wgpAtEe69cu6-bNESsg" ref="resource.md#_kSpKYJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kp2wg5AtEe69cu6-bNESsg" ref="resource.md#_jzZjQJAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kp2whJAtEe69cu6-bNESsg" name="FK_ID_FICHIER_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kp2whZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kp2whpAtEe69cu6-bNESsg" ref="resource.md#_kSsNsJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kp2wh5AtEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_kS1XoZAtEe69cu6-bNESsg" name="DWH_TEL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_kS1XopAtEe69cu6-bNESsg" value="DWH_TEL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_kS1Xo5AtEe69cu6-bNESsg" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_kY0D0JAtEe69cu6-bNESsg" name="SID_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY0D0ZAtEe69cu6-bNESsg" value="SID_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY0D0pAtEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY0D05AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY0D1JAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kY0D1ZAtEe69cu6-bNESsg" name="PHONE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY0D1pAtEe69cu6-bNESsg" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY0q4JAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY0q4ZAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY0q4pAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kY0q45AtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kY0q5JAtEe69cu6-bNESsg" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY0q5ZAtEe69cu6-bNESsg" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY0q5pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY0q55AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY0q6JAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kY0q6ZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kY1R8JAtEe69cu6-bNESsg" name="FAVORI" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY1R8ZAtEe69cu6-bNESsg" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY1R8pAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY1R85AtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY1R9JAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kY1R9ZAtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kY1R9pAtEe69cu6-bNESsg" name="TYPE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY1R95AtEe69cu6-bNESsg" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY1R-JAtEe69cu6-bNESsg" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY1R-ZAtEe69cu6-bNESsg" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY1R-pAtEe69cu6-bNESsg" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kY1R-5AtEe69cu6-bNESsg" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kY15AJAtEe69cu6-bNESsg" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY15AZAtEe69cu6-bNESsg" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY15ApAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY15A5AtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY15BJAtEe69cu6-bNESsg" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kY15BZAtEe69cu6-bNESsg" name="DATE_IMPORT" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY15BpAtEe69cu6-bNESsg" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY15B5AtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY15CJAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY15CZAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kY15CpAtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_kY15C5AtEe69cu6-bNESsg" name="DATE_MAJ" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_kY15DJAtEe69cu6-bNESsg" value="DATE_MAJ"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_kY2gEJAtEe69cu6-bNESsg" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_kY2gEZAtEe69cu6-bNESsg" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_kY2gEpAtEe69cu6-bNESsg" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_kY2gE5AtEe69cu6-bNESsg" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_kY6KcJAtEe69cu6-bNESsg" name="PK_SID_CLIENT_TYPE">
        <node defType="com.stambia.rdbms.colref" id="_kY6KcZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_kY6KcpAtEe69cu6-bNESsg" ref="resource.md#_kY0D0JAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_kY6Kc5AtEe69cu6-bNESsg" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_kY6KdJAtEe69cu6-bNESsg" ref="resource.md#_kY1R9pAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=TYPE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kqZjEJAtEe69cu6-bNESsg" name="FK_SID_CLIENT3_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kqZjEZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kqZjEpAtEe69cu6-bNESsg" ref="resource.md#_kY0D0JAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kqZjE5AtEe69cu6-bNESsg" ref="resource.md#_kpK0AJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=SID_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_kqaKIJAtEe69cu6-bNESsg" name="FK_ID_FICHIER3_DWH">
        <node defType="com.stambia.rdbms.relation" id="_kqaKIZAtEe69cu6-bNESsg" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_kqaKIpAtEe69cu6-bNESsg" ref="resource.md#_kY15AJAtEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_kqaKI5AtEe69cu6-bNESsg" ref="resource.md#_juUO8JAlEe69cu6-bNESsg?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
  </node>
</md:node>