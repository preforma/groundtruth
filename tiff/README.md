# Class
[1](1.md) BigTiff - TIFF with 64 bit offsets

[2](2.md) Tag cardinality - TIFF using a Tag with incorrect cardinality (Other cardinality than specified in Baseline 6.0)

[3](3.md) "Incorrect tag type - TIFF with a Tag with incorrect type but still readable (TIFF readers should accept BYTE, SHORT, or LONG values for any unsigned integer field."

[4](4.md) Incompatible tag type - TIFF using a Tag with incorrect and incompatible type (Other type than specified in Baseline 6.0)

[5](5.md) Channels error - Channels count do not match ( SamplesPerPixel, ExtraSamples and BitsPerSample must have consistency )

[6](6.md) Dimensions error - Incorrect image width/height (the Image width or Height declared not match with the tiled or striped image data structure)

[7](7.md) Resolution error - Missing Resolution (XResolution and YResolution tag) or declared with a zero value

[8](8.md) Missing required tags in an Image IFD Baseline 6.0 - Required tags for defining an Image IFD not present (ImageWidth, ImageLength, Xresolution,Yresolution, PhotometricInterpretation)

[9](9.md) Incorrect page number - A TIFF multipage document (NewSubFileType values 2,3,6 or 7)  with incorrect page number (page numbers must range from zero to the number of images, missing pages, duplicat pages, inconsistent number of pages)

[10](10.md) Unexpected tag type - Unknown tag type (type not defined in Baseline 6.0)

[11](11.md) MagicNumber - Tiff signature not correct (magic number must be 42)

[12](12.md) Byte Order - Incorrect Byte Order (only little endian or big endian are accepted)

[13](13.md) Bad alignment - Offsets in a word boundary

[14](14.md) Bad Offset - IFD or tags offsets pointing outside the file or inside the Image File Header, re-use offsets (offset points or overlapping to already used data)

[15](15.md) IFD entries 0 - Number of IDF entries in an IFD is zero

[16](16.md) No IFDs - At least 1 IFD must exist

[17](17.md) IFD Entry not in ascending order - Tags not ordered in strict ascending order (tags not ordered or duplicate tags)

[18](18.md) Invalid Photometric Interpretation - Photometric Interpretation must be a valid value defined in the TIFF Baseline 6.0

[19](19.md) Coherent strips tags - StripOffsets and StripByteCount cardinalities matching

[20](20.md) Strips tags - StripOffsets, StripByteCounts tags must exist for stripped images

[21](21.md) Consistent strips - Check strips sizes match image dimensions

[22](22.md) Coherent tiles tags - TilesOffsets and TileByteCount cardinalities matching

[23](23.md) Tiles tags - TileOffsets, TileWidth, TileByteCounts and TileLength tags must exist for tiled images

[24](24.md) Valid tile tags - TileWidth, and TileLength greater than zero

[25](25.md) Consistent tiles - Check tiles sizes match image dimensions

[26](26.md) Bilevel - Incorrect tags for Bilevel images

[27](27.md) Grayscale - Incorrect tags for Grayscale images

[28](28.md) Pallete - Incorrect tags for Pallete images (ColorMap and InkSet are mandatory)

[29](29.md) Transparency Mask - Incorrect tags for Transparency mask images

[30](30.md) CMYK - Incorrect tags for CMYK images

[31](31.md) YCbCr - Incorrect tags for YCbCr images

[32](32.md) CIELab - Incorrect tags for CIELab images

[33](33.md) RGB - Incorrect tags for RGB images

[34](34.md) Bad Ascii7 format - Tags with Ascii format containing non-7 bits ascii, Ascii without null character termination,More than one null between strings

[35](35.md) Bad Datetime - Datetime tag with incorrect format, invalid date, incorrect tag type (No ASCII), incorrect cardinality

[36](36.md) Private tags - If more than 10 private tags are used in one IFD, a private IFD should be used to encapsulate them

[37](37.md) TiffEP - Incorrect Tiff EP

[38](38.md) TiffEP StardardID - Incorrect Tiff EP with tag TIFF/EPStandardID

[39](49.md) TiffIT - Incorrect Tiff IT

[40](40.md) Lossy compression - TIFF file using lossy compression

[41](41.md) Forbidden TIA tags - Tiff with forbidden tags (for example: SubfileType, Thresholding, CellWidth, CellLength, FillOrder, MinSampleValue, MaxSampleValue, FreeOffsets, FreeByteCounts, T4Options, T6Options, TransferFunction, Predictor, WhitePoint, PrimaryChromaticities, ColorMap, HalftoneHints, TileWidth, TileLength, TileOffsets, TileByteCounts, SubIFDs, InkSet, InkNames, NumberOfInks, DotRange, TargetPrinter, ExtraSamples, SMinSampleValue, SMaxSampleValue, TransferRange, JPEGTables, JPEGProc, JPEGInterchangeFormat, JPEGInterchangeFormatLngth, JPEGRestartInterval, JPEGLosslessPredictors, JPEGPointTransforms, JPEGQTables, JPEGDCTables, JPEGACTables, YCbCrCoefficients, YCbCrSubSampling, YCbCrPositioning, ReferenceBlackWhite, CFARepeatPatternDim, CFAPattern, Interlace, CompressedBitsPerPixel, FocalPlaneXResolution, FocalPlaneYResolution, ImageSourceData)

[42](42.md) Mandatory TIA tags - Tiff without mandatory TI-A tags (for example: NewSubfileType,ImageWidth, ImageLength, BitsPerSample, Compression, PhotometricInterpretation, StripOffsets, Orientation, SamplesPerPixel, RowsPerStrip, StripByteCounts, PlanarConfiguration)

[43](43.md) Uncompressed Baseline IBM TIFF v6.0 RGB - Image conformance TIFF Baseline 6.0 with little-endian byte order, RGB color without compression

[44](44.md) Size of the uncompressed TIFF-file - Size in the range [X, Y] Mb (depending on the size of the analogue object)

