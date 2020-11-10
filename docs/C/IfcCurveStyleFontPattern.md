IfcCurveStyleFontPattern
========================
{ .extDef}  
> NOTE  Definition according to ISO/CD 10303-46:1992  
> A curve style font pattern is a pair of visible and invisible curve segment
> length measures in presentation area units.  
  
> NOTE  Corresponding ISO 10303 name: curve_style_font_pattern. Please refer
> to ISO/IS 10303-46:1994 for the final definition of the formal standard.  
  
> HISTORY  New entity in IFC2x2.  
[ _bSI
Documentation_](https://standards.buildingsmart.org/IFC/DEV/IFC4_2/FINAL/HTML/schema/ifcpresentationappearanceresource/lexical/ifccurvestylefontpattern.htm)


Attribute definitions
---------------------
| Attribute              | Description                                                                                                                                                                                                                                                                                                |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| VisibleSegmentLength   | The length of the visible segment in the pattern definition.\X\0D> NOTE  For a visible segment representing a point, the value 0. should be assigned.\X\0D\X\0D{ .change-ifc2x3}\X\0D> IFC2x3 CHANGE  The datatype has been changed to IfcLengthMeasure with upward compatibility for file-based exchange. |
| InvisibleSegmentLength | The length of the invisible segment in the pattern definition.                                                                                                                                                                                                                                             |

