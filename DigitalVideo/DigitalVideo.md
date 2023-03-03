#  Graphical representation


__Diagram__




[![Image:Digital_Video_ODP_diagram.png](./Digital_Video_ODP_diagram.png)](../Image/Digital_Video_ODP_diagram.png.md "Image:Digital_Video_ODP_diagram.png")




#  General description




|  |  |
| --- | --- |
|  Name: |  Digital Video |
|  Submitted by: | [PanagiotisMitzias](../User/PanagiotisMitzias.md "User:PanagiotisMitzias"), [MarinaRiga](../User/MarinaRiga.md "User:MarinaRiga"), [EfstratiosKontopoulos](../User/EfstratiosKontopoulos.md "User:EfstratiosKontopoulos") |
|  Also Known As: |  |
|  Intent: |  The pattern intends to model digital video files, their components and other associated entities, such as codecs and containers. This pattern has been developed by [MKLab](http://mklab.iti.gr/ "http://mklab.iti.gr/") at CERTH/ITI for the [PERICLES](http://www.pericles-project.eu/ "http://www.pericles-project.eu/") FP7 project. |
|  Domains: | [Multimedia](../Community/Multimedia.md "Community:Multimedia") |
|  Competency Questions: | <li><i>What does a digital video file consist of?</i> A digital video file usually consists of one or more streams. These streams are compressed using codecs (coder-decoder) and wrapped into a container.</li><li><i>What types of streams exist in a video file?</i> Video streams audio streams and subtitle streams. A video file has at least one video stream and may also have any number and any type of other streams.</li><li><i>What types of codecs exist?</i> Video and audio codecs.</li> |
|  Solution description: |  The pattern’s main entity is a digital video file (DigitalVideo). Appropriate object properties connect the video file with codecs, streams, containers, etc. Additionally, the model includes the most significant descriptors for all the previous notions, such as bitrate, aspect ratio, compression type, etc. |
|  Reusable OWL Building Block: | [http://mklab.iti.gr/pericles/DigitalVideo\_ODP.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://mklab.iti.gr/pericles/DigitalVideo_ODP.owl&message=OWL building block&from_page_id=3855&update=) (850) |
|  Consequences: |  The design pattern is expected to facilitate the creation of digital video domain ontologies that will be exploited in the field of digital preservation. A well-established, comprehensible pattern will prove to be advantageous. |
|  Scenarios: | <li>The digital video is wrapped by an AVI container.</li><li>The digital video has duration 22 minutes.</li><li>The video stream is processed by the QuickTime codec.</li><li>The audio stream has bitrate 256 kbit/s.</li> |
|  Known Uses: |  |
|  Web References: |  |
|  Other References: |  |
|  Examples (OWL files): |  |
|  Extracted From: |  |
|  Reengineered From: |  |
|  Has Components: |  |
|  Specialization Of: |  |
|  Related CPs: |  |


  




#  Elements


_The __DigitalVideo__ Content OP locally defines the following ontology elements:_



[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __DigitalVideo__ (owl:Class) A digital video file. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[DigitalVideo](./DigitalVideo.md "Submissions:DigitalVideo/DigitalVideo") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Codec__ (owl:Class) A codec is a device or computer program capable of encoding or decoding a digital data stream or signal. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Codec](./DigitalVideo/AudioCodec.md "Submissions:DigitalVideo/Codec") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AudioCodec__ (owl:Class) An audio codec is a device or computer program capable of coding or decoding a digital data stream of audio. 
E.g. MP3 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AudioCodec](./DigitalVideo/AudioCodec.md "Submissions:DigitalVideo/AudioCodec") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __VideoCodec__ (owl:Class) A video codec is an electronic circuit or software that compresses or decompresses digital video, thus converting raw (uncompressed) digital video to a compressed format or vice-versa. 
E.g. QuickTime H.264 (Apple's implementation for H.264/MPEG-4 AVC coding format) [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[VideoCodec](./DigitalVideo/VideoCodec.md "Submissions:DigitalVideo/VideoCodec") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Stream__ (owl:Class) A (data) stream is a sequence of digitally encoded coherent signals (packets of data or data packets) used to transmit or receive information that is in the process of being transmitted. The term stream is used here to define raw, uncompressed content (video or audio) prior to being encoded into a wrapper or after being decoded from a wrapper. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Stream](./DigitalVideo/AudioStream.md "Submissions:DigitalVideo/Stream") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AudioStream__ (owl:Class) An audio stream is a stream where the carried data is audio content. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AudioStream](./DigitalVideo/AudioStream.md "Submissions:DigitalVideo/AudioStream") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __VideoStream__ (owl:Class) A video stream is a stream where the carried data is video content. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[VideoStream](./DigitalVideo/hasVideoStream.md "Submissions:DigitalVideo/VideoStream") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __SubtitleStream__ (owl:Class) A subtitle stream is a stream where the carried data is subtitle content for a video. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[SubtitleStream](./DigitalVideo/hasSubtitleStream.md "Submissions:DigitalVideo/SubtitleStream") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Container__ (owl:Class) A container or wrapper format is a metafile format whose specification describes how different elements of data and metadata coexist in a computer file. 
E.g. Matroska (MKV), MP4, etc. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Container](./DigitalVideo/Container.md "Submissions:DigitalVideo/Container") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Descriptor__ (owl:Class) Descriptors are the various elements describing a digital video, a container, a stream or a codec. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[Descriptor](./DigitalVideo/Descriptor.md "Submissions:DigitalVideo/Descriptor") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AnalogBroadcastStandard__ (owl:Class) The video color encoding system, if the video originates from analog television broadcasts. 
E.g. NTSC, PAL, etc. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AnalogBroadcastStandard](./DigitalVideo/AnalogBroadcastStandard.md "Submissions:DigitalVideo/AnalogBroadcastStandard") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __AspectRatio__ (owl:Class) The aspect ratio of an image describes the proportional relationship between its width and its height. It is commonly expressed as two numbers separated by a colon, as in 16:9. 
E.g. 16:9, 4:3, etc. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[AspectRatio](./DigitalVideo/AspectRatio.md "Submissions:DigitalVideo/AspectRatio") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __Bit Rate__ (owl:Class) The bitrate is the data rate for a video or audio file. Video and audio data rates are given in bits per second. 
E.g. 2 MBits/s [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[BitRate](./DigitalVideo/BitRate.md "Submissions:DigitalVideo/BitRate") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __ChromaFormat__ (owl:Class) The chroma subsampling type. Chroma subsampling is the practice of encoding images by implementing less resolution for chroma information than for luma information, taking advantage of the human visual system's lower acuity for color differences than for luminance. 
E.g. 4:2:0 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[ChromaFormat](./DigitalVideo/ChromaFormat.md "Submissions:DigitalVideo/ChromaFormat") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __CodingStandard__ (owl:Class) Also known as coding format or compression format. 
E.g. H.264/MPEG-4 AVC [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[CodingStandard](./DigitalVideo/CodingStandard.md "Submissions:DigitalVideo/CodingStandard") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __ColourSpaceType__ (owl:Class) A color space is a specific organization of colors. It allows for reproducible representations of color, in both analog and digital representations. A color space may be arbitrary, with particular colors assigned to a set of physical color swatches and corresponding assigned names or numbers. 
E.g. YUV, RGB, etc. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[ClourSpaceType](./DigitalVideo/ClourSpaceType.md "Submissions:DigitalVideo/ClourSpaceType") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __CompressionType__ (owl:Class) The type of video compression. 
E.g. lossy, lossless or uncompressed [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[CompressionType](./DigitalVideo/CompressionType.md "Submissions:DigitalVideo/CompressionType") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __EmbeddingType__ (owl:Class) The type of embedment used to attach a subtitle stream to a video. 
E.g. hard, prerendered, soft, etc. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[EmbeddingType](./DigitalVideo/EmbeddingType.md "Submissions:DigitalVideo/EmbeddingType") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __FrameRate__ (owl:Class) Frame rate, also known as frame frequency, is the frequency (rate) at which an imaging device produces unique consecutive images called frames. The term applies equally well to film and video cameras, computer graphics, and motion capture systems. Frame rate is most often expressed in frames per second (FPS) and is also expressed in progressive scan monitors as hertz (Hz). 
E.g. 60 FPS [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[FrameRate](./DigitalVideo/FrameRate.md "Submissions:DigitalVideo/FrameRate") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __FrameSize__ (owl:Class) The dimensions of a video's frame. 
E.g. 1920 x 1080 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[FrameSize](./DigitalVideo/FrameSize.md "Submissions:DigitalVideo/FrameSize") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __PlaybackDuration__ (owl:Class) The duration of a video, video stream or audio stream. 
E.g. 22 minutes [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[PlaybackDuration](./DigitalVideo/hasPlaybackDuration.md "Submissions:DigitalVideo/PlaybackDuration") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __RangeType__ (owl:Class) The type of range a video is created for. 
E.g. broadcast range or full range [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[RangeType](./DigitalVideo/hasRangeType.md "Submissions:DigitalVideo/RangeType") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __SampleRate__ (owl:Class) The audio sample rate is the number of samples of audio carried per second, measured in Hz or kHz (one kHz being 1 000 Hz). For example, 44 100 samples per second can be expressed as either 44 100 Hz, or 44.1 kHz.
The video sample rate of a digital video format determines how often the light intensity of each video line is sampled. 



E.g. 96 kHz, 74.25MHz, etc. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[SampleRate](./DigitalVideo/hasSampleRate.md "Submissions:DigitalVideo/SampleRate") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __ScanType__ (owl:Class) Progressive or interlaced scan. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[ScanType](./DigitalVideo/hasScanType.md "Submissions:DigitalVideo/ScanType") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __SetOfStandards__ (owl:Class) Sets of standards standardize the format of a video stream. 
E.g. BT.601 or BT.709 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[SetOfStandards](./DigitalVideo/hasSetOfStandards.md "Submissions:DigitalVideo/SetOfStandards") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __E.g. SubRip, SubViewer, etc.__ (owl:Class) The file format of subtitles. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[SubtitleTextFormat](./DigitalVideo/hasSubtitleTextFormat.md "Submissions:DigitalVideo/SubtitleTextFormat") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __VideoCodecLevel__ (owl:Class) A video codec level is a specified set of constraints that indicate a degree of required decoder performance for a profile. 
E.g. 4 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[VideoCodecLevel](./DigitalVideo/hasVideoCodecLevel.md "Submissions:DigitalVideo/VideoCodecLevel") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __VideoCodecProfile__ (owl:Class) The video codec profile is a set of capabilities and constraints apllied in the encoder. It allows the decoder to recognize the requirements to decode a specific stream. 
E.g. baseline profile, extended profile, main profile, high profile, etc. [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[VideoCodecProfile](./DigitalVideo/hasVideoCodecProfile.md "Submissions:DigitalVideo/VideoCodecProfile") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __VideoQualityMeasurement__ (owl:Class) Measurement carried out according to the video quality metric. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[VideoQualityMeasurement](./DigitalVideo/hasVideoQualityMeasurement.md "Submissions:DigitalVideo/VideoQualityMeasurement") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __VideoQualityMetric__ (owl:Class) Process or software used to measure the quality of a video. 
E.g. VQM [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[VideoQualityMetric](./DigitalVideo/hasVideoQualityMetric.md "Submissions:DigitalVideo/VideoQualityMetric") page_
[![Class](./20px-Class.gif)](../Image/Class.gif.md "Class") __YUVSampleRange__ (owl:Class) YUV Sample Range 
E.g. 16-235 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[YUVSampleRange](./DigitalVideo/hasYUVSampleRange.md "Submissions:DigitalVideo/YUVSampleRange") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasBitRate__ (owl:ObjectProperty) Associates an audio or video stream with a bit rate. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasBitRate](./DigitalVideo/hasBitRate.md "Submissions:DigitalVideo/hasBitRate") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __wrappedBy__ (owl:ObjectProperty) Associates a digital video file with a container type. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[wrappedBy](./DigitalVideo/wrappedBy.md "Submissions:DigitalVideo/wrappedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasStream__ (owl:ObjectProperty) Associates a digital video with a stream. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasStream](./DigitalVideo/hasStream.md "Submissions:DigitalVideo/hasStream") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAudioStream__ (owl:ObjectProperty) Associates a digital video with an audio stream. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAudioStream](./DigitalVideo/hasAudioStream.md "Submissions:DigitalVideo/hasAudioStream") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasVideoStream__ (owl:ObjectProperty) Associates a digital video with a video stream. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasVideoStream](./DigitalVideo/hasVideoStream.md "Submissions:DigitalVideo/hasVideoStream") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSubtitleStream__ (owl:ObjectProperty) Associates a digital video with a subtitle stream. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSubtitleStream](./DigitalVideo/hasSubtitleStream.md "Submissions:DigitalVideo/hasSubtitleStream") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCodingStandard__ (owl:ObjectProperty) Associates a video or audio stream with a coding standard. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCodingStandard](./DigitalVideo/hasCodingStandard.md "Submissions:DigitalVideo/hasCodingStandard") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasRangeType__ (owl:ObjectProperty) Associates a video stream with a range type. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasRangeType](./DigitalVideo/hasRangeType.md "Submissions:DigitalVideo/hasRangeType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasVideoQualityMeasurement__ (owl:ObjectProperty) Associates a video stream with a video quality measurement. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasVideoQualityMeasurement](./DigitalVideo/hasVideoQualityMeasurement.md "Submissions:DigitalVideo/hasVideoQualityMeasurement") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasChromaFormat__ (owl:ObjectProperty) Associates a video stream with a chroma format. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasChromaFormat](./DigitalVideo/hasChromaFormat.md "Submissions:DigitalVideo/hasChromaFormat") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasEmbeddingType__ (owl:ObjectProperty) Associates a subtitle stream with an embedding type. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasEmbeddingType](./DigitalVideo/hasEmbeddingType.md "Submissions:DigitalVideo/hasEmbeddingType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAspectRatio__ (owl:ObjectProperty) Associates a video stream with an aspect ratio. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAspectRatio](./DigitalVideo/hasAspectRatio.md "Submissions:DigitalVideo/hasAspectRatio") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSubtitleTextFormat__ (owl:ObjectProperty) Associates a subtitle stream with a subtitle text format. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSubtitleTextFormat](./DigitalVideo/hasSubtitleTextFormat.md "Submissions:DigitalVideo/hasSubtitleTextFormat") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasVideoQualityMetric__ (owl:ObjectProperty) Associates a video stream with a video quality metric. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasVideoQualityMetric](./DigitalVideo/hasVideoQualityMetric.md "Submissions:DigitalVideo/hasVideoQualityMetric") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasCompressionType__ (owl:ObjectProperty) Associates a video or audio codec with a compression type. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasCompressionType](./DigitalVideo/hasCompressionType.md "Submissions:DigitalVideo/hasCompressionType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasScanType__ (owl:ObjectProperty) Associates a video stream with a scan type. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasScanType](./DigitalVideo/hasScanType.md "Submissions:DigitalVideo/hasScanType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasVideoCodecProfile__ (owl:ObjectProperty) Associates a video codec with a video codec profile. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasVideoCodecProfile](./DigitalVideo/hasVideoCodecProfile.md "Submissions:DigitalVideo/hasVideoCodecProfile") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasColourSpaceType__ (owl:ObjectProperty) Associates a video stream with a colour space type. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasColourSpaceType](./DigitalVideo/hasColourSpaceType.md "Submissions:DigitalVideo/hasColourSpaceType") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasFrameSize__ (owl:ObjectProperty) Associates a video stream with a frame size. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasFrameSize](./DigitalVideo/hasFrameSize.md "Submissions:DigitalVideo/hasFrameSize") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSetOfStandards__ (owl:ObjectProperty) Associates a video stream with a set of standards. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSetOfStandards](./DigitalVideo/hasSetOfStandards.md "Submissions:DigitalVideo/hasSetOfStandards") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __processedBy__ (owl:ObjectProperty) Associates a stream with a codec. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[processedBy](./DigitalVideo/processedBy.md "Submissions:DigitalVideo/processedBy") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasAnalogBroadcastStandard__ (owl:ObjectProperty) Associates a digital video with an analog broadcast standard. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasAnalogBroadcastStandard](./DigitalVideo/hasAnalogBroadcastStandard.md "Submissions:DigitalVideo/hasAnalogBroadcastStandard") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasVideoCodecLevel__ (owl:ObjectProperty) Associates a video codec with a video codec level. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasVideoCodecLevel](./DigitalVideo/hasVideoCodecLevel.md "Submissions:DigitalVideo/hasVideoCodecLevel") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasFrameRate__ (owl:ObjectProperty) Associates a video stream with a frame rate. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasFrameRate](./DigitalVideo/hasFrameRate.md "Submissions:DigitalVideo/hasFrameRate") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasPlaybackDuration__ (owl:ObjectProperty) Associates a digital video, a video stream or an audio stream with a playback duration. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasPlaybackDuration](./DigitalVideo/hasPlaybackDuration.md "Submissions:DigitalVideo/hasPlaybackDuration") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasYUVSampleRange__ (owl:ObjectProperty) Associates a video stream with a YUV sample range. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasYUVSampleRange](./DigitalVideo/hasYUVSampleRange.md "Submissions:DigitalVideo/hasYUVSampleRange") page_
[![ObjectProperty](./20px-ObjectProperty.gif)](../Image/ObjectProperty.gif.md "ObjectProperty") __hasSampleRate__ (owl:ObjectProperty) Associates a video stream or audio stream with a sample rate. 
 [![](./11px-ArrowRight.gif)](../Image/ArrowRight.gif.md "ArrowRight.gif") _[hasSampleRate](./DigitalVideo/hasSampleRate.md "Submissions:DigitalVideo/hasSampleRate") page_
#  Additional information


#  Scenarios



__Scenarios about DigitalVideo__
No scenario is added to this Content OP.




#  Reviews



__Reviews about DigitalVideo__
There is no review about this proposal.
This revision (revision ID __13288__) takes in account the reviews: none


Other info at [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DigitalVideo&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DigitalVideo&action=evaluation")




  




#  Modeling issues



__Modeling issues about DigitalVideo__
There is no Modeling issue related to this proposal.




  




#  References


* The homepage of the PERICLES project that supported the development of this ODP. [Project Home Page](http://www.pericles-project.eu/ "http://www.pericles-project.eu/") | [reference page](../Community/References/PERICLES_project_homepage.md "Community:References/PERICLES project homepage")* The paper presenting the ODP that was accepted for publication in the WOP'15 proceedings. [Workshop publication](http://ceur-ws.org/Vol-1461/WOP2015_pattern_abstract_4.pdf "http://ceur-ws.org/Vol-1461/WOP2015_pattern_abstract_4.pdf") | [reference page](../Community/References/An_Ontology_Design_Pattern_for_Digital_Video.md "Community:References/An Ontology Design Pattern for Digital Video")

  






|  |  Submission to event[WOP:2015](../WOP/2015.md "WOP:2015") |
| --- | --- |