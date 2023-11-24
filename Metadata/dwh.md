<?xml version="1.0" encoding="UTF-8"?>
<md:node xmlns:md="http://www.stambia.com/md" defType="com.stambia.rdbms.server" id="_CHAaQIUmEe6BKsDnQj9IRA" name="dwh" md:ref="resource.md#UUID_MD_RDBMS_ORACLE?fileId=UUID_MD_RDBMS_ORACLE$type=md$name=Oracle?" internalVersion="v1.0.0">
  <attribute defType="com.stambia.rdbms.server.module" id="_CHN1oIUmEe6BKsDnQj9IRA" value="Oracle"/>
  <attribute defType="com.stambia.rdbms.server.user" id="_QjlYkIUmEe6BKsDnQj9IRA" value="CSG1_ORA2"/>
  <attribute defType="com.stambia.rdbms.server.driver" id="_QjlYkYUmEe6BKsDnQj9IRA" value="oracle.jdbc.OracleDriver"/>
  <attribute defType="com.stambia.rdbms.server.designerAutoCommit" id="_Qjl_oIUmEe6BKsDnQj9IRA" value="true"/>
  <attribute defType="com.stambia.rdbms.server.password" id="_Qjl_oYUmEe6BKsDnQj9IRA" value="6F23E4E8A3281AF328EB08370AA8572A"/>
  <attribute defType="com.stambia.rdbms.server.url" id="_Qjl_ooUmEe6BKsDnQj9IRA" value="jdbc:oracle:thin:@195.83.93.26:1521/SIAD_PDB2"/>
  <node defType="com.stambia.rdbms.schema" id="_CKpkIIUmEe6BKsDnQj9IRA" name="CSG1_ORA2">
    <attribute defType="com.stambia.rdbms.schema.name" id="_CK3mkIUmEe6BKsDnQj9IRA" value="CSG1_ORA2"/>
    <attribute defType="com.stambia.rdbms.schema.rejectMask" id="_CK4NoIUmEe6BKsDnQj9IRA" value="R_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.loadMask" id="_CK4NoYUmEe6BKsDnQj9IRA" value="L[number]_[targetName]"/>
    <attribute defType="com.stambia.rdbms.schema.integrationMask" id="_CK4NooUmEe6BKsDnQj9IRA" value="I_[targetName]"/>
    <node defType="com.stambia.rdbms.datastore" id="_QjvwoYUmEe6BKsDnQj9IRA" name="SAS_CLIENT">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_QjvwooUmEe6BKsDnQj9IRA" value="SAS_CLIENT"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Qjvwo4UmEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Qp9GUIUmEe6BKsDnQj9IRA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GUYUmEe6BKsDnQj9IRA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GUoUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GU4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GVIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GVYUmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GVoUmEe6BKsDnQj9IRA" name="CLE_COMPTE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GV4UmEe6BKsDnQj9IRA" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GWIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GWYUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GWoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GW4UmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GXIUmEe6BKsDnQj9IRA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GXYUmEe6BKsDnQj9IRA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GXoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GX4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GYIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GYYUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GYoUmEe6BKsDnQj9IRA" name="TYPE" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GY4UmEe6BKsDnQj9IRA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GZIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GZYUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GZoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GZ4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GaIUmEe6BKsDnQj9IRA" name="CIVILITE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GaYUmEe6BKsDnQj9IRA" value="CIVILITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GaoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9Ga4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GbIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GbYUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GboUmEe6BKsDnQj9IRA" name="PRENOM" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9Gb4UmEe6BKsDnQj9IRA" value="PRENOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GcIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GcYUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GcoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9Gc4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GdIUmEe6BKsDnQj9IRA" name="NOM" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GdYUmEe6BKsDnQj9IRA" value="NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GdoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9Gd4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GeIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GeYUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GeoUmEe6BKsDnQj9IRA" name="DATE_ANNIVERSAIRE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9Ge4UmEe6BKsDnQj9IRA" value="DATE_ANNIVERSAIRE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GfIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GfYUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GfoUmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9Gf4UmEe6BKsDnQj9IRA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GgIUmEe6BKsDnQj9IRA" name="SEXE" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GgYUmEe6BKsDnQj9IRA" value="SEXE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GgoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9Gg4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GhIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GhYUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GhoUmEe6BKsDnQj9IRA" name="MUTUELLE" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9Gh4UmEe6BKsDnQj9IRA" value="MUTUELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GiIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GiYUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GioUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9Gi4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GjIUmEe6BKsDnQj9IRA" name="ID_FICHIER" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GjYUmEe6BKsDnQj9IRA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9GjoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9Gj4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GkIUmEe6BKsDnQj9IRA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qp9GkYUmEe6BKsDnQj9IRA" name="DATE_IMPORT" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qp9GkoUmEe6BKsDnQj9IRA" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qp9Gk4UmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qp9GlIUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qp9GlYUmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qp9GloUmEe6BKsDnQj9IRA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_QqG3UIUmEe6BKsDnQj9IRA" name="PK_CLIENT">
        <node defType="com.stambia.rdbms.colref" id="_QqG3UYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_QqG3UoUmEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_RNXVYIUmEe6BKsDnQj9IRA" name="FK_COMPTE">
        <node defType="com.stambia.rdbms.relation" id="_RNXVYYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_RNXVYoUmEe6BKsDnQj9IRA" ref="resource.md#_Qp9GVoUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_RNXVY4UmEe6BKsDnQj9IRA" ref="resource.md#_Q1Le4IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_RNXVZIUmEe6BKsDnQj9IRA" name="SYS_C0015467">
        <node defType="com.stambia.rdbms.relation" id="_RNXVZYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_RNXVZoUmEe6BKsDnQj9IRA" ref="resource.md#_Qp9GjIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_RNXVZ4UmEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zHLZYIUvEe6BKsDnQj9IRA" name="SYS_C0016738">
        <node defType="com.stambia.rdbms.relation" id="_zHLZYYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zHLZYoUvEe6BKsDnQj9IRA" ref="resource.md#_Qp9GjIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zHLZY4UvEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zHLZZIUvEe6BKsDnQj9IRA" name="SYS_C0016737">
        <node defType="com.stambia.rdbms.relation" id="_zHLZZYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zHLZZoUvEe6BKsDnQj9IRA" ref="resource.md#_Qp9GVoUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zHLZZ4UvEe6BKsDnQj9IRA" ref="resource.md#_Q1Le4IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_5AfZUIUzEe6BKsDnQj9IRA" name="SYS_C0016794">
        <node defType="com.stambia.rdbms.relation" id="_5AfZUYUzEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_5AfZUoUzEe6BKsDnQj9IRA" ref="resource.md#_Qp9GjIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_5AfZU4UzEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_5AfZVIUzEe6BKsDnQj9IRA" name="SYS_C0016793">
        <node defType="com.stambia.rdbms.relation" id="_5AfZVYUzEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_5AfZVoUzEe6BKsDnQj9IRA" ref="resource.md#_Qp9GVoUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_5AfZV4UzEe6BKsDnQj9IRA" ref="resource.md#_Q1Le4IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_RHohH4UmEe6BKsDnQj9IRA" name="SAS_TEL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_RHohIIUmEe6BKsDnQj9IRA" value="SAS_TEL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_RHohIYUmEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_RMw4cIUmEe6BKsDnQj9IRA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_RMw4cYUmEe6BKsDnQj9IRA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RMw4coUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RMw4c4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RMw4dIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RMw4dYUmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RMw4doUmEe6BKsDnQj9IRA" name="PHONE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_RMw4d4UmEe6BKsDnQj9IRA" value="PHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RMw4eIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RMw4eYUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RMw4eoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RMw4e4UmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RMw4fIUmEe6BKsDnQj9IRA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_RMw4fYUmEe6BKsDnQj9IRA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RMw4foUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_RMw4f4UmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RMw4gIUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RMw4gYUmEe6BKsDnQj9IRA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RMw4goUmEe6BKsDnQj9IRA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RMw4g4UmEe6BKsDnQj9IRA" name="FAVORI" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_RMw4hIUmEe6BKsDnQj9IRA" value="FAVORI"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RMw4hYUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_RMw4hoUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RMw4h4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RMw4iIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RMw4iYUmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RMw4ioUmEe6BKsDnQj9IRA" name="TYPE" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_RMw4i4UmEe6BKsDnQj9IRA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RMw4jIUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RMw4jYUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RMw4joUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RMw4j4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RMw4kIUmEe6BKsDnQj9IRA" name="ID_FICHIER" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_RMw4kYUmEe6BKsDnQj9IRA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RMw4koUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RMw4k4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RMw4lIUmEe6BKsDnQj9IRA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RM2_EIUmEe6BKsDnQj9IRA" name="DATE_IMPORT" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM2_EYUmEe6BKsDnQj9IRA" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RM2_EoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RM2_E4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RM2_FIUmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RM2_FYUmEe6BKsDnQj9IRA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_RM2_FoUmEe6BKsDnQj9IRA" name="SYS_C0016798">
        <node defType="com.stambia.rdbms.colref" id="_RM2_F4UmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_RM2_GIUmEe6BKsDnQj9IRA" ref="resource.md#_RMw4cIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
        <node defType="com.stambia.rdbms.colref" id="_RM2_GYUmEe6BKsDnQj9IRA" position="2">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_RM2_GoUmEe6BKsDnQj9IRA" ref="resource.md#_RMw4ioUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=TYPE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ROTwkIUmEe6BKsDnQj9IRA" name="SYS_C0015475">
        <node defType="com.stambia.rdbms.relation" id="_ROTwkYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ROTwkoUmEe6BKsDnQj9IRA" ref="resource.md#_RMw4cIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ROTwk4UmEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_ROTwlIUmEe6BKsDnQj9IRA" name="SYS_C0015476">
        <node defType="com.stambia.rdbms.relation" id="_ROTwlYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_ROTwloUmEe6BKsDnQj9IRA" ref="resource.md#_RMw4kIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_ROTwl4UmEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_zGrqLIUvEe6BKsDnQj9IRA" name="STATUS_TELEPHONE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_zGrqLYUvEe6BKsDnQj9IRA" value="STATUS_TELEPHONE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_zGrqLoUvEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_zGrqL4UvEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_zGrqMIUvEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_zGrqMYUvEe6BKsDnQj9IRA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_zGrqMoUvEe6BKsDnQj9IRA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zIMGAIUvEe6BKsDnQj9IRA" name="SYS_C0016747">
        <node defType="com.stambia.rdbms.relation" id="_zIMGAYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zIMGAoUvEe6BKsDnQj9IRA" ref="resource.md#_RMw4kIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zIMGA4UvEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zIMGBIUvEe6BKsDnQj9IRA" name="SYS_C0016746">
        <node defType="com.stambia.rdbms.relation" id="_zIMGBYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zIMGBoUvEe6BKsDnQj9IRA" ref="resource.md#_RMw4cIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zIMGB4UvEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_5BVG0IUzEe6BKsDnQj9IRA" name="SYS_C0016800">
        <node defType="com.stambia.rdbms.relation" id="_5BVG0YUzEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_5BVG0oUzEe6BKsDnQj9IRA" ref="resource.md#_RMw4kIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_5BVG04UzEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_5BVG1IUzEe6BKsDnQj9IRA" name="SYS_C0016799">
        <node defType="com.stambia.rdbms.relation" id="_5BVG1YUzEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_5BVG1oUzEe6BKsDnQj9IRA" ref="resource.md#_RMw4cIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_5BVG14UzEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Qv-OwYUmEe6BKsDnQj9IRA" name="SAS_COMPTE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Qv-OwoUmEe6BKsDnQj9IRA" value="SAS_COMPTE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Qv-Ow4UmEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Q1Le4IUmEe6BKsDnQj9IRA" name="CLE_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q1Le4YUmEe6BKsDnQj9IRA" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q1Le4oUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q1Le44UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q1Le5IUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q1Le5YUmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q1Le5oUmEe6BKsDnQj9IRA" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q1Le54UmEe6BKsDnQj9IRA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q1Le6IUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q1Le6YUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q1Le6oUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q1Le64UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q1Le7IUmEe6BKsDnQj9IRA" name="TYPE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q1Le7YUmEe6BKsDnQj9IRA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q1Le7oUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q1Le74UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q1Le8IUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q1Le8YUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q1Le8oUmEe6BKsDnQj9IRA" name="CABINET_RATTACHEMENT" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q1Le84UmEe6BKsDnQj9IRA" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q1Le9IUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q1Le9YUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q1Le9oUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q1Le94UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q1Le-IUmEe6BKsDnQj9IRA" name="ID_FICHIER" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q1Le-YUmEe6BKsDnQj9IRA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q1Le-oUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q1Le-4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q1Le_IUmEe6BKsDnQj9IRA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q1Le_YUmEe6BKsDnQj9IRA" name="DATE_IMPORT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q1Le_oUmEe6BKsDnQj9IRA" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q1Le_4UmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q1LfAIUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q1LfAYUmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q1LfAoUmEe6BKsDnQj9IRA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_Q1LfA4UmEe6BKsDnQj9IRA" name="PK_COMPTE">
        <attribute defType="com.stambia.rdbms.pk.remarks" id="_BrRF8Iq3Ee6eAd0POgdy0A" value="test surl'existence du champ CLE_COMPTE représentant la PK de la table "/>
        <attribute defType="com.stambia.rdbms.pk.userMessage" id="_GPKu8Iq3Ee6eAd0POgdy0A" value="PK_COMPTE n'existe pas "/>
        <attribute defType="com.stambia.rdbms.pk.rejectCode" id="_Hfg8gIq3Ee6eAd0POgdy0A" value="PK_COMPTE"/>
        <attribute defType="com.stambia.rdbms.pk.severity" id="_H467AIq3Ee6eAd0POgdy0A" value="200"/>
        <node defType="com.stambia.rdbms.colref" id="_Q1LfBIUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_Q1LfBYUmEe6BKsDnQj9IRA" ref="resource.md#_Q1Le4IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_COMPTE?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_RNnNAIUmEe6BKsDnQj9IRA" name="SYS_C0015464">
        <node defType="com.stambia.rdbms.relation" id="_RNnNAYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_RNnNAoUmEe6BKsDnQj9IRA" ref="resource.md#_Q1Le-IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_RNnNA4UmEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zHlCAIUvEe6BKsDnQj9IRA" name="SYS_C0016735">
        <node defType="com.stambia.rdbms.relation" id="_zHlCAYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zHlCAoUvEe6BKsDnQj9IRA" ref="resource.md#_Q1Le-IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zHlCA4UvEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_5A1XkIUzEe6BKsDnQj9IRA" name="SYS_C0016791">
        <node defType="com.stambia.rdbms.relation" id="_5A1XkYUzEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_5A1XkoUzEe6BKsDnQj9IRA" ref="resource.md#_Q1Le-IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_5A1Xk4UzEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Q1RlgYUmEe6BKsDnQj9IRA" name="SAS_COMPTE1">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Q1RlgoUmEe6BKsDnQj9IRA" value="SAS_COMPTE1"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Q1Rlg4UmEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Q4qQsIUmEe6BKsDnQj9IRA" name="CLE_COMPTE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q4qQsYUmEe6BKsDnQj9IRA" value="CLE_COMPTE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q4qQsoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q4qQs4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q4qQtIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q4qQtYUmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q4qQtoUmEe6BKsDnQj9IRA" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q4qQt4UmEe6BKsDnQj9IRA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q4qQuIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q4qQuYUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q4qQuoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q4qQu4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q4qQvIUmEe6BKsDnQj9IRA" name="TYPE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q4qQvYUmEe6BKsDnQj9IRA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q4qQvoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q4qQv4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q4qQwIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q4qQwYUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q4qQwoUmEe6BKsDnQj9IRA" name="CABINET_RATTACHEMENT" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q4qQw4UmEe6BKsDnQj9IRA" value="CABINET_RATTACHEMENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q4qQxIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q4qQxYUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q4qQxoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q4qQx4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q4qQyIUmEe6BKsDnQj9IRA" name="ID_FICHIER" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q4qQyYUmEe6BKsDnQj9IRA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q4qQyoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q4qQy4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q4qQzIUmEe6BKsDnQj9IRA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q4qQzYUmEe6BKsDnQj9IRA" name="DATE_IMPORT" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q4qQzoUmEe6BKsDnQj9IRA" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q4qQz4UmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q4qQ0IUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q4qQ0YUmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q4qQ0oUmEe6BKsDnQj9IRA" value="7"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Q4wXUYUmEe6BKsDnQj9IRA" name="SAS_ADRESSE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Q4wXUoUmEe6BKsDnQj9IRA" value="SAS_ADRESSE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Q4wXU4UmEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Q-ek0IUmEe6BKsDnQj9IRA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-ek0YUmEe6BKsDnQj9IRA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-ek0oUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-ek04UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-ek1IUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-ek1YUmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-ek1oUmEe6BKsDnQj9IRA" name="STATUS" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-ek14UmEe6BKsDnQj9IRA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-ek2IUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Q-ek2YUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-ek2oUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-ek24UmEe6BKsDnQj9IRA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-ek3IUmEe6BKsDnQj9IRA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-ek3YUmEe6BKsDnQj9IRA" name="LIGNE_1" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-ek3oUmEe6BKsDnQj9IRA" value="LIGNE_1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-ek34UmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-ek4IUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-ek4YUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-ek4oUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-ek44UmEe6BKsDnQj9IRA" name="LIGNE_2" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-ek5IUmEe6BKsDnQj9IRA" value="LIGNE_2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-ek5YUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-ek5oUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-ek54UmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-ek6IUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-krcIUmEe6BKsDnQj9IRA" name="LIGNE_3" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krcYUmEe6BKsDnQj9IRA" value="LIGNE_3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-krcoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-krc4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-krdIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-krdYUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-krdoUmEe6BKsDnQj9IRA" name="LIGNE_4" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krd4UmEe6BKsDnQj9IRA" value="LIGNE_4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-kreIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-kreYUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-kreoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-kre4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-krfIUmEe6BKsDnQj9IRA" name="LIGNE_5" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krfYUmEe6BKsDnQj9IRA" value="LIGNE_5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-krfoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-krf4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-krgIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-krgYUmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-krgoUmEe6BKsDnQj9IRA" name="VILLE" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krg4UmEe6BKsDnQj9IRA" value="VILLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-krhIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-krhYUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-krhoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-krh4UmEe6BKsDnQj9IRA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-kriIUmEe6BKsDnQj9IRA" name="CODE_POSTAL" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-kriYUmEe6BKsDnQj9IRA" value="CODE_POSTAL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-krioUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-kri4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-krjIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-krjYUmEe6BKsDnQj9IRA" value="5"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-krjoUmEe6BKsDnQj9IRA" name="PAYS" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krj4UmEe6BKsDnQj9IRA" value="PAYS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-krkIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Q-krkYUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-krkoUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-krk4UmEe6BKsDnQj9IRA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-krlIUmEe6BKsDnQj9IRA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-krlYUmEe6BKsDnQj9IRA" name="QUALITE" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krloUmEe6BKsDnQj9IRA" value="QUALITE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-krl4UmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Q-krmIUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-krmYUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-krmoUmEe6BKsDnQj9IRA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-krm4UmEe6BKsDnQj9IRA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-krnIUmEe6BKsDnQj9IRA" name="ID_FICHIER" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krnYUmEe6BKsDnQj9IRA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-krnoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-krn4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-kroIUmEe6BKsDnQj9IRA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Q-kroYUmEe6BKsDnQj9IRA" name="DATE_IMPORT" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_Q-krooUmEe6BKsDnQj9IRA" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Q-kro4UmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Q-krpIUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Q-krpYUmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Q-krpoUmEe6BKsDnQj9IRA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_Q-krp4UmEe6BKsDnQj9IRA" name="SYS_C0016742">
        <node defType="com.stambia.rdbms.colref" id="_Q-krqIUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_Q-krqYUmEe6BKsDnQj9IRA" ref="resource.md#_Q-ek0IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_RN0BUIUmEe6BKsDnQj9IRA" name="SYS_C0015472">
        <node defType="com.stambia.rdbms.relation" id="_RN0BUYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_RN0BUoUmEe6BKsDnQj9IRA" ref="resource.md#_Q-ek0IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_RN0BU4UmEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_RN0BVIUmEe6BKsDnQj9IRA" name="SYS_C0015473">
        <node defType="com.stambia.rdbms.relation" id="_RN0BVYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_RN0BVoUmEe6BKsDnQj9IRA" ref="resource.md#_Q-krnIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_RN0BV4UmEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zH2HwIUvEe6BKsDnQj9IRA" name="SYS_C0016744">
        <node defType="com.stambia.rdbms.relation" id="_zH2HwYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zH2HwoUvEe6BKsDnQj9IRA" ref="resource.md#_Q-krnIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zH2Hw4UvEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zH2HxIUvEe6BKsDnQj9IRA" name="SYS_C0016743">
        <node defType="com.stambia.rdbms.relation" id="_zH2HxYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zH2HxoUvEe6BKsDnQj9IRA" ref="resource.md#_Q-ek0IUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zH2Hx4UvEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_QqG3VIUmEe6BKsDnQj9IRA" name="SOURCE">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_QqG3VYUmEe6BKsDnQj9IRA" value="SOURCE"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_QqG3VoUmEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_Qv4IIIUmEe6BKsDnQj9IRA" name="ID_FICHIER" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qv4IIYUmEe6BKsDnQj9IRA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qv4IIoUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qv4II4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qv4IJIUmEe6BKsDnQj9IRA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qv4IJYUmEe6BKsDnQj9IRA" name="NOM_FICHIER" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qv4IJoUmEe6BKsDnQj9IRA" value="NOM_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qv4IJ4UmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qv4IKIUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qv4IKYUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qv4IKoUmEe6BKsDnQj9IRA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Qv4IK4UmEe6BKsDnQj9IRA" name="DATE_IMPORT" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_Qv4ILIUmEe6BKsDnQj9IRA" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Qv4ILYUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Qv4ILoUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Qv4IL4UmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Qv4IMIUmEe6BKsDnQj9IRA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_Qv4IMYUmEe6BKsDnQj9IRA" name="SYS_C0016789">
        <node defType="com.stambia.rdbms.colref" id="_Qv4IMoUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_Qv4IM4UmEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_Q-uccYUmEe6BKsDnQj9IRA" name="SAS_EMAIL">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_Q-uccoUmEe6BKsDnQj9IRA" value="SAS_EMAIL"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_Q-ucc4UmEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_RECaQIUmEe6BKsDnQj9IRA" name="CLE_CLIENT" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_RECaQYUmEe6BKsDnQj9IRA" value="CLE_CLIENT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RECaQoUmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RECaQ4UmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RECaRIUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RECaRYUmEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RECaRoUmEe6BKsDnQj9IRA" name="EMAIL" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_RECaR4UmEe6BKsDnQj9IRA" value="EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RECaSIUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RECaSYUmEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RECaSoUmEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RECaS4UmEe6BKsDnQj9IRA" value="255"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RECaTIUmEe6BKsDnQj9IRA" name="STATUS" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_RECaTYUmEe6BKsDnQj9IRA" value="STATUS"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RECaToUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_RECaT4UmEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RECaUIUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RECaUYUmEe6BKsDnQj9IRA" value="NUMBER"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RECaUoUmEe6BKsDnQj9IRA" value="1"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RECaU4UmEe6BKsDnQj9IRA" name="ID_FICHIER" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_RECaVIUmEe6BKsDnQj9IRA" value="ID_FICHIER"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RECaVYUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RECaVoUmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RECaV4UmEe6BKsDnQj9IRA" value="NUMBER"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RECaWIUmEe6BKsDnQj9IRA" name="DATE_IMPORT" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_RECaWYUmEe6BKsDnQj9IRA" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RECaWoUmEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RECaW4UmEe6BKsDnQj9IRA" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RECaXIUmEe6BKsDnQj9IRA" value="DATE"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RECaXYUmEe6BKsDnQj9IRA" value="7"/>
      </node>
      <node defType="com.stambia.rdbms.pk" id="_RECaXoUmEe6BKsDnQj9IRA" name="SYS_C0016795">
        <node defType="com.stambia.rdbms.colref" id="_RECaX4UmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.colref.ref" id="_RECaYIUmEe6BKsDnQj9IRA" ref="resource.md#_RECaQIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_RN9yUIUmEe6BKsDnQj9IRA" name="SYS_C0015469">
        <node defType="com.stambia.rdbms.relation" id="_RN9yUYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_RN9yUoUmEe6BKsDnQj9IRA" ref="resource.md#_RECaQIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_RN9yU4UmEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_RN9yVIUmEe6BKsDnQj9IRA" name="SYS_C0015470">
        <node defType="com.stambia.rdbms.relation" id="_RN9yVYUmEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_RN9yVoUmEe6BKsDnQj9IRA" ref="resource.md#_RECaU4UmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_RN9yV4UmEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.column" id="_y8-UjIUvEe6BKsDnQj9IRA" name="STATUS_EMAIL" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_y8-UjYUvEe6BKsDnQj9IRA" value="STATUS_EMAIL"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_y8-UjoUvEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_y8-Uj4UvEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_y8-UkIUvEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_y8-UkYUvEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_y8-UkoUvEe6BKsDnQj9IRA" value="45"/>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zH7nUIUvEe6BKsDnQj9IRA" name="SYS_C0016741">
        <node defType="com.stambia.rdbms.relation" id="_zH7nUYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zH7nUoUvEe6BKsDnQj9IRA" ref="resource.md#_RECaU4UmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zH7nU4UvEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_zH7nVIUvEe6BKsDnQj9IRA" name="SYS_C0016740">
        <node defType="com.stambia.rdbms.relation" id="_zH7nVYUvEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_zH7nVoUvEe6BKsDnQj9IRA" ref="resource.md#_RECaQIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_zH7nV4UvEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_5BFPMIUzEe6BKsDnQj9IRA" name="SYS_C0016797">
        <node defType="com.stambia.rdbms.relation" id="_5BFPMYUzEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_5BFPMoUzEe6BKsDnQj9IRA" ref="resource.md#_RECaU4UmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_5BFPM4UzEe6BKsDnQj9IRA" ref="resource.md#_Qv4IIIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=ID_FICHIER?"/>
        </node>
      </node>
      <node defType="com.stambia.rdbms.fk" id="_5BFPNIUzEe6BKsDnQj9IRA" name="SYS_C0016796">
        <node defType="com.stambia.rdbms.relation" id="_5BFPNYUzEe6BKsDnQj9IRA" position="1">
          <attribute defType="com.stambia.rdbms.relation.fk" id="_5BFPNoUzEe6BKsDnQj9IRA" ref="resource.md#_RECaQIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
          <attribute defType="com.stambia.rdbms.relation.pk" id="_5BFPN4UzEe6BKsDnQj9IRA" ref="resource.md#_Qp9GUIUmEe6BKsDnQj9IRA?fileId=_CHAaQIUmEe6BKsDnQj9IRA$type=md$name=CLE_CLIENT?"/>
        </node>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_ygdXpIUvEe6BKsDnQj9IRA" name="TRANSCO">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_ygdXpYUvEe6BKsDnQj9IRA" value="TRANSCO"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_ygdXpoUvEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_yjsR0IUvEe6BKsDnQj9IRA" name="TYPE" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_yjsR0YUvEe6BKsDnQj9IRA" value="TYPE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_yjsR0oUvEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_yjsR04UvEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_yjsR1IUvEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_yjsR1YUvEe6BKsDnQj9IRA" value="50"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_yjsR1oUvEe6BKsDnQj9IRA" name="CODE" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_yjsR14UvEe6BKsDnQj9IRA" value="CODE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_yjsR2IUvEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_yjsR2YUvEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_yjsR2oUvEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_yjsR24UvEe6BKsDnQj9IRA" value="10"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_yj2C0IUvEe6BKsDnQj9IRA" name="LIBELLE" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_yj2C0YUvEe6BKsDnQj9IRA" value="LIBELLE"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_yj2C0oUvEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_yj2C04UvEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_yj2C1IUvEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_yj2C1YUvEe6BKsDnQj9IRA" value="255"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_RJWsNIUzEe6BKsDnQj9IRA" name="SAS_FILESRC">
      <attribute defType="com.stambia.rdbms.datastore.name" id="_RJWsNYUzEe6BKsDnQj9IRA" value="SAS_FILESRC"/>
      <attribute defType="com.stambia.rdbms.datastore.type" id="_RJWsNoUzEe6BKsDnQj9IRA" value="TABLE"/>
      <node defType="com.stambia.rdbms.column" id="_RM_PAIUzEe6BKsDnQj9IRA" name="FILE_NOM" position="1">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM_PAYUzEe6BKsDnQj9IRA" value="FILE_NOM"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RM_PAoUzEe6BKsDnQj9IRA" value="0"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RM_PA4UzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RM_PBIUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RM_PBYUzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="_0GkVYIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RM_PBoUzEe6BKsDnQj9IRA" name="F1" position="2">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM_PB4UzEe6BKsDnQj9IRA" value="F1"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RM_PCIUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RM_PCYUzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RM_PCoUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RM_PC4UzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="_0cVKAIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RM_PDIUzEe6BKsDnQj9IRA" name="F2" position="3">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM_PDYUzEe6BKsDnQj9IRA" value="F2"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RM_PDoUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RM_PD4UzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RM_PEIUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RM_PEYUzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="_0y7sIIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RM_PEoUzEe6BKsDnQj9IRA" name="F3" position="4">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM_PE4UzEe6BKsDnQj9IRA" value="F3"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RM_PFIUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RM_PFYUzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RM_PFoUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RM_PF4UzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="_1G-pgIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RM_PGIUzEe6BKsDnQj9IRA" name="F4" position="5">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM_PGYUzEe6BKsDnQj9IRA" value="F4"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RM_PGoUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RM_PG4UzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RM_PHIUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RM_PHYUzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="_-YeDAIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RM_PHoUzEe6BKsDnQj9IRA" name="F5" position="6">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM_PH4UzEe6BKsDnQj9IRA" value="F5"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RM_PIIUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RM_PIYUzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RM_PIoUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RM_PI4UzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTekIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RM_PJIUzEe6BKsDnQj9IRA" name="F6" position="7">
        <attribute defType="com.stambia.rdbms.column.name" id="_RM_PJYUzEe6BKsDnQj9IRA" value="F6"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVoIUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVoYUzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVooUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVo4UzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTekYq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RNFVpIUzEe6BKsDnQj9IRA" name="F7" position="8">
        <attribute defType="com.stambia.rdbms.column.name" id="_RNFVpYUzEe6BKsDnQj9IRA" value="F7"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVpoUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVp4UzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVqIUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVqYUzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTekoq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RNFVqoUzEe6BKsDnQj9IRA" name="F8" position="9">
        <attribute defType="com.stambia.rdbms.column.name" id="_RNFVq4UzEe6BKsDnQj9IRA" value="F8"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVrIUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVrYUzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVroUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVr4UzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTek4q3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RNFVsIUzEe6BKsDnQj9IRA" name="F9" position="10">
        <attribute defType="com.stambia.rdbms.column.name" id="_RNFVsYUzEe6BKsDnQj9IRA" value="F9"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVsoUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVs4UzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVtIUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVtYUzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTelIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RNFVtoUzEe6BKsDnQj9IRA" name="F10" position="11">
        <attribute defType="com.stambia.rdbms.column.name" id="_RNFVt4UzEe6BKsDnQj9IRA" value="F10"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVuIUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVuYUzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVuoUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVu4UzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTelYq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RNFVvIUzEe6BKsDnQj9IRA" name="F11" position="12">
        <attribute defType="com.stambia.rdbms.column.name" id="_RNFVvYUzEe6BKsDnQj9IRA" value="F11"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVvoUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVv4UzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVwIUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVwYUzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTeloq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RNFVwoUzEe6BKsDnQj9IRA" name="F12" position="13">
        <attribute defType="com.stambia.rdbms.column.name" id="_RNFVw4UzEe6BKsDnQj9IRA" value="F12"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVxIUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVxYUzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVxoUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVx4UzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTel4q3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_RNFVyIUzEe6BKsDnQj9IRA" name="F13" position="14">
        <attribute defType="com.stambia.rdbms.column.name" id="_RNFVyYUzEe6BKsDnQj9IRA" value="F13"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_RNFVyoUzEe6BKsDnQj9IRA" value="1"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_RNFVy4UzEe6BKsDnQj9IRA" value="CHAR"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_RNFVzIUzEe6BKsDnQj9IRA" value="VARCHAR2"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_RNFVzYUzEe6BKsDnQj9IRA" value="50"/>
        <attribute defType="com.stambia.rdbms.column.disableCDC" id="__cTemIq3Ee6eAd0POgdy0A" value="true"/>
      </node>
      <node defType="com.stambia.rdbms.column" id="_Iwu6gIq8Ee6eAd0POgdy0A" name="DATE_IMPORT" position="15">
        <attribute defType="com.stambia.rdbms.column.name" id="_Iwu6gYq8Ee6eAd0POgdy0A" value="DATE_IMPORT"/>
        <attribute defType="com.stambia.rdbms.column.nullable" id="_Iwu6goq8Ee6eAd0POgdy0A" value="1"/>
        <attribute defType="com.stambia.rdbms.column.digits" id="_Iwu6g4q8Ee6eAd0POgdy0A" value="6"/>
        <attribute defType="com.stambia.rdbms.column.charByte" id="_Iwu6hIq8Ee6eAd0POgdy0A" value="BYTE"/>
        <attribute defType="com.stambia.rdbms.column.type" id="_Iwu6hYq8Ee6eAd0POgdy0A" value="TIMESTAMP"/>
        <attribute defType="com.stambia.rdbms.column.size" id="_Iwu6hoq8Ee6eAd0POgdy0A" value="11"/>
      </node>
    </node>
    <node defType="com.stambia.rdbms.datastore" id="_csqioYqqEe6eAd0POgdy0A"/>
  </node>
</md:node>