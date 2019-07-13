## Weight and center gravity techniques calculation for basic weight accounting database

### Introduction

Today with any 3D cad system on the market engineering management are often convinced by these software suppliers that their systems can replace mass properties engineers and mass properties developed techniques and tools over the past years.

The worksheet “BOM some cg calculation scenario - preliminary requirement for weight accounting database.xlsx” present some techniques used to properly calculate assemblies weight with respective center of gravity and details unit weight when 3D information has not been defined in the 3D models or requirements coming from other regulations like [REACH](https://echa.europa.eu/regulations/reach/understanding-reach) is not implemented in their software. These techniques help to minimise errors when properly used and when limitations are well known by mass properties engineers.

These techniques should be implemented when you decide to develop a basic weight accounting database to support mass properties engineer accounting task. When some of these techniques are implemented, training should be provided to non mass properties engineer if your intent is to use these engineers to populate the database in a collaborative work Environment with mass properties engineer.

**Source File:** BOM some cg calculation scenario - preliminary requirement for weight accounting database.xlsx

**File Includes:**
- Worksheets from "Assy A" to "Assy D multiple location"
   - Includes the process to calculate properly the CG according to 4 possible scenarios,
	 - Worksheets "Assy B instance 1" and "Assy B instance 2"
       - are the same assybly but they are not located at the same place.
     - Worksheet “Assy C”
       - Is an assembly with partial center of gravity information.
     - Worksheet “Assy D multiple location”
       - Is an assembly with no provided gravity information.

- Worksheet «Catalog"
  - Includes list of details used in the assemblies “weight and CG calcsheet”. The “Unit Weight Calculated” fields use parameters for calculation. These parameters are often used for unit weight unit weight calc, but they are not the only one used in industries.

- Worksheets " Material Spec", “Chemical Finish”, “Paint Spec”, “Mfg Variation”
  - Are the parameter data used by “Unit Weight Calculated” in worksheet «Catalog"
