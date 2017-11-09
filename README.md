# Atlantis-Character-sheet

<div class="sheet-primary-info-col-left">
	<!-- ===== Primary Info ===== -->
	<div class="sheet-header">
		<div class=section-name">PRIMARY INFO</div>
	<div>
	<div class="sheet-section-name-primary-info>
		<input type="text" name="attr_charactername" placeholder="Character">
		<input type="text" name="attr_level" placeholder="Level">
		<input type="text" name="attr_race" placeholder="Race">
		<input type="text" name="attr_profession" placeholder="Profession">
		</div>
</div>    
  
<div class="sheet-primary-info-col-left">
<!-- ===== Secondary Info ===== -->
	<div class="sheet-header">
		<div class=section-name">SECONDARY INFO</div>
	<div>
	<div class="sheet-section-name-secondary-info>
		<input type="text" name="attr_XP" placeholder="XP">
		<input type="text" name="attr_XP Pool" placeholder="XP Pool">
		<input type="text" name="attr_Combat Training"  placeholder="Combat Training">
		<input type="text" name="attr_Alignment" placeholder="Alignment">
		<input type="text" name="attr_Birthplace" placeholder="Birthplace">	
		<input type="text" name="attr_Background" placeholder="Background">
		<input type="text" name="attr_Racial or Special ablilities" placeholder="Racial or Special abilities">
		<input type="text" name="attr_Renown" placeholder="Renown">
		<div>
<div>


                                                         

<table style="width:50%">
  <tr>
    <th>Attribute</th>
    <th>Score</th> 
    <th>Modifier</th>
    <th>Save</th>
    <th>SaveRoll</th>
    <th>Bonus</th>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Strength" placeholder=Strength /><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Strength" placeholder=Score /><td> 
    <td><input type="number" class="sheet-Attribute" name="Modifier" placeholder=Modifier /><td>
    <td><input type="number" class="sheet-Attribute" name="STRSave" placeholder=STRSave /><td>
    <td><button type='roll' value='/roll 1d20 + @{STRSave}' name='roll_STRSave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus" placeholder=Bonus /<td>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Speed"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Speed"/><td> 
    <td><input type="number" class="sheet-Attribute" name="attr_Modifier"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_SPDSave"/><td>
    <td><button type='roll' value='/roll 1d20 + @{SPDSave}' name='roll_SPDSave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus"></td>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Dexterity"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Dexterity"/><td> 
    <td><input type="number" class="sheet-Attribute" name="attr_Modifier"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_DEXSave"/><td>
    <td><button type='roll' value='/roll 1d20 + @{DEXSave}' name='roll_DEXSave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus"></td>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Constitution"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Constitution"/><td> 
    <td><input type="number" class="sheet-Attribute" name="attr_Modifier"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_CONSave"/><td>
    <td><button type='roll' value='/roll 1d20 + @{CONSave}' name='roll_CONSave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus"></td>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Intelligence"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Intelligence"/><td> 
    <td><input type="number" class="sheet-Attribute" name="attr_Modifier"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_INTSave"/><td>
    <td><button type='roll' value='/roll 1d20 + @{INTSave}' name='roll_INTSave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus"></td>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Willpower"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Willpower"/><td> 
    <td><input type="number" class="sheet-Attribute" name="attr_Modifier"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_WILSave"/><td>
    <td><button type='roll' value='/roll 1d20 + @{WILSave}' name='roll_WILSave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus"></td>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Charisma"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Charisma"/><td> 
    <td><input type="number" class="sheet-Attribute" name="attr_Modifier"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_CHASave"/><td>
    <td><button type='roll' value='/roll 1d20 + @{CHASave}' name='roll_CHASave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus"></td>
  </tr>
  <tr>
    <td><input type="text"class="sheet-Attribute" name="attr_Perception"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_Perception"/><td> 
    <td><input type="number" class="sheet-Attribute" name="attr_Modifier"/><td>
    <td><input type="number" class="sheet-Attribute" name="attr_PERSave"/><td>
    <td><button type='roll' value='/roll 1d20 + @{PERSave}' name='roll_PERSave'></button><td>
    <td><input type="text" class="sheet-Attribute" name="attr_Bonus"/><td>
  </tr>
</table>

