---
layout: default-layout
title: Dynamsoft Barcode Reader Reference - Main Page
description: Dynamsoft Barcode Reader Parameter Reference - Main Page
keywords: barcode reader parameter, parameter reference, parameters
needAutoGenerateSidebar: false
---

# Parameter Reference

## Capture Vision Template

| Parameter Name | Description |
| -------------- | ----------- |
| [`ImageROIProcessingNameArray`]({{ site.dcv_parameters_reference }}capture-vision-template/image-roi-processing-name-array.html) | Defines the collection of image ROI processing object names, used to refer to the `TargetROIDef` objects. |
| [`ImageSourceName`]({{ site.dcv_parameters_reference }}capture-vision-template/image-source-name.html) | Indicates the input source name, used to refer to the `ImageSource` object. |
| [`MaxParallelTasks`]({{ site.dcv_parameters_reference }}capture-vision-template/max-parallel-tasks.html) | Defines the maximum number of parallel tasks for the DCV runtime. |
| [`Name`]({{ site.dcv_parameters_reference }}capture-vision-template/name.html) | Defines the name of a `CaptureVisionTemplate` object, which serves as its unique identifier. |
| [`OutputOriginalImage`]({{ site.dcv_parameters_reference }}capture-vision-template/output-original-Image.html) | Indicates whether DCV finally outputs the original input image. |
| [`Timeout`]({{ site.dcv_parameters_reference }}capture-vision-template/timeout.html) | Defines the maximum amount of time (in milliseconds) that should be spent processing each image or frame. |

## Target ROI Def

| Parameter Name  | Description |
| --------------- | ----------- |
| [`BaseTargetROIDefName`]({{ site.dcv_parameters_reference }}target-roi-def/base-target-roidef-name.html) | Represents the name of another `TargetROIDef` object to inherit from. |
| [`Location`]({{ site.dcv_parameters_reference }}target-roi-def/location.html) | Defines the location of the TargetROI with `reference objects` filter conditions and `offset` parameters. |
| [`Name`]({{ site.dcv_parameters_reference }}}target-roi-def/name.html) | Defines the name of a `TargetROIDef` object, which serves as its unique identifier. |
| [`PauseFlag`]({{ site.dcv_parameters_reference }}target-roi-def/pause-flag.html) | Indicates that the region results generated by this `TargetROIDef` will not be used by other `TargetROIDef` objects that depend on it to calculate the target regions, unless the user explicitly performs an update operation. |
| [`TaskSettingNameArray`]({{ site.dcv_parameters_reference }}target-roi-def/task-setting-name-array.html) | Parameter `TaskSettingNameArray` represents the collection of task setting object names, used to refer to the `BarcodeReaderTaskSetting`, `LabelRecognizerTaskSetting`, `DocumentNormalizerTaskSetting` objects. |

## Barcode Reader Task Setting

| Parameter Name | Description |
| -------------- | ----------- |
| [`BarcodeColourModes`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/barcode-colour-modes.html) | Defines the barcode colour modes. |
| [`BarcodeComplementModes`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/barcode-complement-modes.html) | Defines how to complement the missing parts of a barcode. |
| [`BarcodeFormatIds`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/barcode-format-ids.html) | Defines the formats of the barcode to process. |
| [`BaseBarcodeReaderTaskSettingName`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/base-barcode-reader-task-setting-name.html) | Represents the name of another `BarcodeReaderTaskSetting` object to inherit from. |
| [`DeblurModes`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/deblur-modes.html) | Defines the mode and priority for deblurring. |
| [`DeformationResistingModes`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/deformation-resisting-modes.html) | Defines how to handle distorted and deformed barcodes. |
| [`DPMCodeReadingModes`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/dpm-code-reading-modes.html) | Defines how to read direct part mark (DPM) barcodes. |
| [`ExpectedBarcodesCount`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/expected-barcodes-count.html) | Defines the number of barcodes expected to be detected. |
| [`LocalizationModes`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/localization-modes.html) | Defines how to localize barcodes. |
| [`MaxThreadsInOneTask`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/max-threads-in-one-task.html) | Defines the maximum threads that can be consumed in one task. |
| [`Name`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/name.html) | Defines the name of a `BarcodeReaderTaskSetting` object, which serves as its unique identifier. |
| [`ReturnBarcodeZoneClarity`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/return-barcode-zone-clarity.html) | Defines whether to return the clarity of the barcode zone. |
| [`SectionImageParameterArray`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/section-image-parameter-array.html) | Defines `ImageParameter` in section unit. |
| [`StartSection`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/start-section.html) | Defines the start section of the algorithm task. |
| [`TerminateSetting`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/terminate-setting.html) | Defines the terminate stages of the task. |
| [`TextResultOrderModes`]({{ site.dcv_parameters_reference }}barcode-reader-task-settings/text-result-order-modes.html) | Defines the order of the returned text results. |

## ImageParameter

| Parameter Name | Description |
| ---------------------------------- | ----------- |
| [`BaseImageParameterName`]({{ site.dcv_parameters_reference }}image-parameter/base-image-parameter-name.html) | Represents the name of another `ImageParameter` object to inherit from. |
| [`BinarizationModes`]({{ site.dcv_parameters_reference }}image-parameter/binarization-modes.html) | Defines the process of binarization |
| [`ColourChannelUsageType`]({{ site.dcv_parameters_reference }}image-parameter/colour-channel-usage-type.html) | Defines how to use the colour channel from the source image buffer. |
| [`ColourConversionModes`]({{ site.dcv_parameters_reference }}image-parameter/colour-conversion-modes.html) | Defines how to convert a colour image to a grayscale image. |
| [`GrayscaleEnhancementModes`]({{ site.dcv_parameters_reference }}image-parameter/grayscale-enhancement-modes.html) | Defines the image processing methods to enhance the quality of the grayscale image. |
| [`GrayscaleTransformationModes`]({{ site.dcv_parameters_reference }}image-parameter/grayscale-transformation-modes.html) | Defines whether or not to invert the color of the grayscale image. |
| [`IfEraseTextZone`]({{ site.dcv_parameters_reference }}image-parameter/if-erase-text-zone.html) | Defines whether to erase the detected text zone. |
| [`Name`]({{ site.dcv_parameters_reference }}image-parameter/name.html) | Defines the name of a `ImageParameter` object, which serves as its unique identifier. |
| [`RegionPredetectionModes`]({{ site.dcv_parameters_reference }}image-parameter/region-predetection-modes.html) | Defines how to find a region of interest (ROI) within the image or frame. |
| [`ScaleDownThreshold`]({{ site.dcv_parameters_reference }}image-parameter/scale-down-threshold.html) | Defines the threshold for image shrinking. |
| [`ScaleUpModes`]({{ site.dcv_parameters_reference }}image-parameter/scale-up-modes.html) | Defines the scale-up process when targets in the image are too small. |
| [`TextDetectionMode`]({{ site.dcv_parameters_reference }}image-parameter/text-detection-mode.html) | Defines how to detect the text area. |
| [`TextureDetectionModes`]({{ site.dcv_parameters_reference }}image-parameter/texture-detection-modes.html) | Defines how to detect texture on an image. |

## Barcode Format Specification

| Parameter Name   | Description |
| ---------------- | ----------- |
| [`AllModuleDeviation`]({{ site.dcv_parameters_reference }}barcode-format-specification/all-module-deviation.html) | Defines the width deviation value (in moduleSize) of a non-standard 1D barcode type relative to the standard barcode width. |
| [`AustralianPostEncodingTable`]({{ site.dcv_parameters_reference }}barcode-format-specification/australian-post-encoding-table.html) | Defines the encoding table used to code the Customer Information Field of Australian Post Customer Barcode. |
| [`BarcodeAngleRangeArray`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-angle-range-array.html) | Defines the range of angles (in degrees) for barcodes searching and result filtering. |
| [`BarcodeBytesLengthRangeArray`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-bytes-length-range-array.html) | Defines the range of barcode bytes length for barcodes searching and result filtering. |
| [`BarcodeHeightRangeArray`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-height-range-array.html) | Defines the range of heights (in pixels) for barcodes searching and result filtering. |
| [`BarcodeTextLengthRangeArray`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-text-length-range-array.html) | Defines the range of barcode text length for barcodes searching and result filtering. |
| [`BarcodeTextRegExPattern`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-text-regex-pattern.html) | Defines the regular expression pattern of barcode text characters for barcodes searching and result filtering. |
| [`BarcodeWidthRangeArray`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-width-range-array.html) | Defines the range of widths (in pixels) for barcodes searching and result filtering. |
| [`BarcodeZoneBarCountRangeArray`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-zone-bar-count-range-array.html) | Defines the range of bar count of the barcode zone for barcodes searching. |
| [`BarcodeZoneMinDistanceToImageBorders`]({{ site.dcv_parameters_reference }}barcode-format-specification/barcode-zone-min-distance-to-image-borders.html) | Defines the minimum distance (in pixels) between the barcode zone and image borders. |
| [`Code128Subset`]({{ site.dcv_parameters_reference }}barcode-format-specification/code128-subset.html) | Defines the subset of Code 128. |
| [`EnableAddonCode`]({{ site.dcv_parameters_reference }}barcode-format-specification/enable-addon-code.html) | Defines whether to identify addon code. |
| [`EnableDataMatrixECC000-140`]({{ site.dcv_parameters_reference }}barcode-format-specification/enable-data-matrix-ecc000-140.html) | Defines whether to read Data Matrix ECC000-140 barcode. |
| [`EnableQRCodeModel1`]({{ site.dcv_parameters_reference }}barcode-format-specification/enable-qr-code-model-1.html) | Defines whether to read QR code model 1. |
| [`FindUnevenModuleBarcode`]({{ site.dcv_parameters_reference }}barcode-format-specification/find-uneven-module-barcode.html) | Defines whether to find barcodes with uneven barcode modules. |
| [`HeadModuleRatio`]({{ site.dcv_parameters_reference }}barcode-format-specification/head-module-ratio.html) | Defines the module count and module size ratio of the barcode head section. |
| [`MinQuietZoneWidth`]({{ site.dcv_parameters_reference }}barcode-format-specification/min-quiet-zone-width.html) | Defines the minimum width (in moduleSize) of the barcode quiet zone. |
| [`MinRatioOfBarcodeZoneWidthToHeight`]({{ site.dcv_parameters_reference }}barcode-format-specification/min-ratio-of-barcode-zone-width-to-height.html) | Defines the minimum ratio (width/height as a percentage) of the barcode zone. |
| [`MinResultConfidence`]({{ site.dcv_parameters_reference }}barcode-format-specification/min-result-confidence.html) | Defines the minimum confidence of the result. |
| [`MirrorMode`]({{ site.dcv_parameters_reference }}barcode-format-specification/mirror-mode.html) | Defines whether to decode mirrored barcodes. |
| [`ModuleSizeRangeArray`]({{ site.dcv_parameters_reference }}barcode-format-specification/module-size-range-array.html) | Defines the range of module size (in pixels) while barcode searching and result filtering. |
| [`MSICodeCheckDigitCalculation`]({{ site.dcv_parameters_reference }}barcode-format-specification/msi-code-check-digit-calculation.html) | Defines the scheme used for calculating a check digit of an MSI barcode. |
| [`Name`]({{ site.dcv_parameters_reference }}barcode-format-specification/name.html) | Defines the name of a `BarcodeFormatSpecification` object, which serves as its unique identifier. |
| [`PartitionModes`]({{ site.dcv_parameters_reference }}barcode-format-specification/partition-modes.html) | Defines the mode to apply partition process when decoding QRCode and DataMatrix. |
| [`PatchCodeSearchingMargin`]({{ site.dcv_parameters_reference }}barcode-format-specification/patch-code-searching-margins.html) | Defines the patch code searching margins. |
| [`RequireStartStopChars`]({{ site.dcv_parameters_reference }}barcode-format-specification/require-start-stop-chars.html) | Defines whether the start and stop characters are required when searching for common 1D barcodes. |
| [`ReturnPartialBarcodeValue`]({{ site.dcv_parameters_reference }}barcode-format-specification/return-partial-barcode-value.html) | Defines whether to return partial barcode value(s). |
| [`StandardFormat`]({{ site.dcv_parameters_reference }}barcode-format-specification/standard-format.html) | Defines the standard barcode format. |
| [`TailModuleRatio`]({{ site.dcv_parameters_reference }}barcode-format-specification/tail-module-ratio.html) | Defines the module count and module size ratio of the barcode tail section. |
| [`VerifyCheckDigit`]({{ site.dcv_parameters_reference }}barcode-format-specification/verify-check-digit.html) | Defines whether to verify the check digit in barcodes where this check digit is optional. |

## Image Source Options

| Parameter Name | Description |
| -------------------- | ----------- |
| [`DirectoryPath`]({{ site.dcv_parameters_reference }}image-source-options/directory-path.html) | Defines a path when the library have to read files. |
| [`FileFilter`]({{ site.dcv_parameters_reference }}image-source-options/file-filter.html) | Defines a file name filter string, which determines which files are fetched. |
| [`Name`]({{ site.dcv_parameters_reference }}image-source-options/name.html) | Defines the name of a `ImageSource` object, which serves as its unique identifier. |
| [`PDFReadingMode`]({{ site.dcv_parameters_reference }}image-source-options/pdf-reading-mode.html) | Defines how to handle PDF files. |
| [`Recursive`]({{ site.dcv_parameters_reference }}image-source-options/recursive.html) | Defines whether to fetch files recursively. |
| [`Type`]({{ site.dcv_parameters_reference }}image-source-options/type.html) | Defines the type of the ImageSource object, which helps CVR create the correct type of image source. |

## Global Parameter

| Parameter Name  | Description |
| ---------------------------- | ----------- |
| [`MaxTotalImageDimension`]({{ site.dcv_parameters_reference }}global-parameter/max-total-image-dimension.html) | Defines the maximum total dimension of the images that read in the memory. |
