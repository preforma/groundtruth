# Class
[0](0.md) Correct - Some correct files.

[1](1.md) EBML-ELEM-START - The first element must be the EBML header.

[2](2.md) EBML-VER-COH - EBMLVersion validity.

[3](3.md) EBML-DOCVER-COH - DocTypeVersion validity.

[4](4.md) EBML-ELEMENT-VALID-PARENT - All elements must have valid parents.

[5](5.md) EBML-ELEMENT-NONMULTIPLES - Elements must follow maxOccurs.

[6](6.md) EBML-ELEMENT-CONTAINS-MANDATES - Elements must follow minOccurs.

[7](7.md) EBML-VALID-MAXID - EBMLMaxIDLength validity.

[8](8.md) EBML-VALID-MAXSIZE - EBMLMaxSizeLength validity.

[9](9.md) EBML-HEADER-ELEMENTS-WITHIN-MAXIDLENGTH - Header elements in element ID length range.

[10](10.md) EBML-ELEMENTS-WITHIN-MAXIDLENGTH - Elements in element ID length range (Deprecated).

[11](11.md) EBML-HEADER-ELEMENTS-WITHIN-MAXIDLENGTH - Header Elements in element data size length range.

[12](12.md) EBML-ELEMENTS-WITHIN-MAXSIZELENGTH - Elements in element data size length range.

[13](13.md) EBML-VINT-EFF - EBML vint efficiency (Deprecated).

[14](14.md) MKV-KNOWN-ELEM - Element ID registered (Deprecated).

[15](15.md) EBML-ELEM-UNKNOWN-SIZE - Element Size 0x7F Reservation.

[16](16.md) EBML-ELEM-SIZE-CAP - Element size byte length limit (Deprecated).

[17](17.md) EBML-ELEM-SIZE-UNK - Element size unknown (Deprecated).

[18](18.md) EBML-WITHIN-SIZE-LIMIT - Element data within size limits.

[19](19.md) EBML-ASCII-ONLY-IN-STRING - ASCII-only data in string.

[20](20.md) MKV-SEEK-RESOLVE - The Matroska seek elements properly resolve.

[21](21.md) EBML-CRC-FIRST - EBML CRC element must be first.

[22](22.md) EBML-CRC-VALID - EBML CRC element must contain a valid hash.

[23](23.md) EBML-CRC-LENGTH - EBML CRC element must use a valid length (Deprecated).

[24](24.md) EBML-MINVER-COHERANT - EBML elements used correlate to DocVersion.

[25](25.md) EBML-MAXVER-COHERANT - EBML elements used correlate to DocVersion.

[26](26.md) EBML-DOCTYPEREADVERSION-COHERANT - EBML elements used correlate to DocTypeReadVersion.

[27](27.md) MKV-SEGMENT-UID-LENGTH - Matroska segment element must use a valid length (Deprecated).

[28](28.md) EBML-ELEMENT-IN-SIZE-RANGE - EBML element adhers to size restrictions.

[29](29.md) EBML-ELEMENT-VALID-RANGE - EBML element adhers to range restrictions.

[30](30.md) MKV-VALID-TRACKTYPE-VALUE - Matroska TrackType validity.

[31](31.md) MKV-VALID-BOOLEANS - Matroska boolean elements validity (Deprecated).

[32](32.md) MKV-NUMERICAL-TAGS - Matroska tags defined as numerical should be.

[33](33.md) FFV1-HEADER-version-OUTOFBAND - Version 3 must have out of band data.

[34](34.md) FFV1-HEADER-version-LATERVERSION - Version must be one of the defined versions.

[35](35.md) FFV1-HEADER-version-EXPERIMENTAL - Version must not be experimental.

[36](36.md) FFV1-HEADER-micro_version-EXPERIMENTAL - micro_version must not be experimental.

[37](37.md) FFV1-HEADER-coder_type - coder_type validity.

[38](38.md) FFV1-HEADER-state_transition_delta - state_transition_delta validity.

[39](39.md) FFV1-HEADER-colorspace_type - colorspace_type validity.

[40](40.md) FFV1-HEADER-bits_per_raw_sample - bits_per_raw_sample coherency.

[41](41.md) FFV1-HEADER-num_h_slices - num_h_slices validity.

[42](42.md) FFV1-HEADER-num_v_slices - num_v_slices validity.

[43](43.md) FFV1-HEADER-FFV1-HEADER-quant_table_count - quant_table_count coherency.

[44](44.md) FFV1-HEADER-v_chroma_subsample-int - (Deprecated).

[45](45.md) FFV1-HEADER-QUANTIZATION_TABLES - Quantization tables coherency.

[46](46.md) FFV1-HEADER-initial_state_delta - initial_state_delta coherency.

[47](47.md) FFV1-HEADER-ec - ec flag validity.

[48](48.md) FFV1-HEADER-intra - intra flag validity.

[49](49.md) FFV1-HEADER-configuration_record_crc_parity - Header CRC must contain a valid hash.

[50](50.md) FFV1-HEADER-END

[51](51.md) FFV1-SLICE-slice_xywh - Slice position and size must be contained in the slices array.

[52](52.md) FFV1-SLICE-quant_table_index - quant_table_index validity.

[53](53.md) FFV1-SLICE-picture_structure - picture_structure validity.

[54](54.md) FFV1-SLICE-sar_den - sar_den coherency.

[55](55.md) FFV1-SLICE-slice_size - slice_size coherency.

[56](56.md) FFV1-SLICE-crc_parity - (Deprecated).

[57](57.md) FFV1-SLICE-slice_crc_parity - Slice CRC must contain a valid hash.

[58](58.md) FFV1-SLICE-SliceContent - Slice CRC must contain a valid hash.

[59](59.md) FFV1-FRAME-END - Frame must end correctly.

[60](60.md) PCM-IS-VALID - (Deprecated).

[61](61.md) MKV-V4+ - Matroska version 4 or greater.

[62](62.md) MKV-SEGMENTUID-PRESENT - SegmentUID presence.

[63](63.md) MKV-SEEKHEAD-PRESENT - SeekHead presence.

[64](64.md) MKV-INTERLACEMENT-CLARITY - Interlaced video clarification.

[65](65.md) MKV-SAMPLE-RANGE-CLARITY - Video sample range clarification.

[66](66.md) MKV-COLOUR-PRIMARY-CLARITY - Video colour primary clarification.

[67](67.md) FFV1-SLICE-error_status - error_status validity.

[68](68.md) FFV1-FRAME-key_frame-ISNOTINTRA - key_frame coherency.

[69](69.md) EBML-NO-JUNK-IN-FIXEDSIZE - No junk bytes if the size of an element is fixed.

# Reproducibility

When feasible, classes document a programmatic method to generate a test file that should trigger the associated implementation check. These methods require ffmpeg 3.3, xmlstarlet, mkvparse, and/or sfk to perform.

