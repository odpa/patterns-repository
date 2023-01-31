# 

 Graphical representation



__Diagram__ 





[![Image:Digital_Video_ODP_diagram.png](images/6/6a/Digital_Video_ODP_diagram.png)](../Image/Digital_Video_ODP_diagram.png "Image:Digital_Video_ODP_diagram.png")





# 

 General description




|  |  |
| --- | --- |
|  Name:  |  Digital Video  |
|  Submitted by:  | [PanagiotisMitzias](../User/PanagiotisMitzias "User:PanagiotisMitzias")  , [MarinaRiga](../User/MarinaRiga "User:MarinaRiga")  , [EfstratiosKontopoulos](../User/EfstratiosKontopoulos "User:EfstratiosKontopoulos")  |
|  Also Known As:  |  |
|  Intent:  |  The pattern intends to model digital video files, their components and other associated entities, such as codecs and containers. This pattern has been developed by [MKLab](http://mklab.iti.gr/ "http://mklab.iti.gr/")  at CERTH/ITI for the [PERICLES](http://www.pericles-project.eu/ "http://www.pericles-project.eu/")  FP7 project.  |
|  Domains:  | [Multimedia](../Community/Multimedia "Community:Multimedia")  |
|  Competency Questions:  | <li><i>        What does a digital video file consist of?       </i>       A digital video file usually consists of one or more streams. These streams are compressed using codecs (coder-decoder) and wrapped into a container.      </li><li><i>        What types of streams exist in a video file?       </i>       Video streams audio streams and subtitle streams. A video file has at least one video stream and may also have any number and any type of other streams.      </li><li><i>        What types of codecs exist?       </i>       Video and audio codecs.      </li> |
|  Solution description:  |  The pattern’s main entity is a digital video file (DigitalVideo). Appropriate object properties connect the video file with codecs, streams, containers, etc. Additionally, the model includes the most significant descriptors for all the previous notions, such as bitrate, aspect ratio, compression type, etc.  |
|  Reusable OWL Building Block:  | [http://mklab.iti.gr/pericles/DigitalVideo\_ODP.owl](http://ontologydesignpatterns.org/wiki/index.php?title=Special:ClickHandler&link=http://mklab.iti.gr/pericles/DigitalVideo_ODP.owl&message=OWL building block&from_page_id=3855&update=)  (850)  |
|  Consequences:  |  The design pattern is expected to facilitate the creation of digital video domain ontologies that will be exploited in the field of digital preservation. A well-established, comprehensible pattern will prove to be advantageous.  |
|  Scenarios:  | <li>       The digital video is wrapped by an AVI container.      </li><li>       The digital video has duration 22 minutes.      </li><li>       The video stream is processed by the QuickTime codec.      </li><li>       The audio stream has bitrate 256 kbit/s.      </li> |
|  Known Uses:  |  |
|  Web References:  |  |
|  Other References:  |  |
|  Examples (OWL files):  |  |
|  Extracted From:  |  |
|  Reengineered From:  |  |
|  Has Components:  |  |
|  Specialization Of:  |  |
|  Related CPs:  |  |



  





# 

 Elements



_The
 __DigitalVideo__ 
 Content OP locally defines the following ontology elements:_ 





[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__DigitalVideo__ 
 (owl:Class) A digital video file.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[DigitalVideo](../Submissions/DigitalVideo/DigitalVideo "Submissions:DigitalVideo/DigitalVideo") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Codec__ 
 (owl:Class) A codec is a device or computer program capable of encoding or decoding a digital data stream or signal.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Codec](../Submissions/DigitalVideo/Codec "Submissions:DigitalVideo/Codec") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AudioCodec__ 
 (owl:Class) An audio codec is a device or computer program capable of coding or decoding a digital data stream of audio. 
E.g. MP3
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AudioCodec](../Submissions/DigitalVideo/AudioCodec "Submissions:DigitalVideo/AudioCodec") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VideoCodec__ 
 (owl:Class) A video codec is an electronic circuit or software that compresses or decompresses digital video, thus converting raw (uncompressed) digital video to a compressed format or vice-versa. 
E.g. QuickTime H.264 (Apple's implementation for H.264/MPEG-4 AVC coding format)
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VideoCodec](../Submissions/DigitalVideo/VideoCodec "Submissions:DigitalVideo/VideoCodec") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Stream__ 
 (owl:Class) A (data) stream is a sequence of digitally encoded coherent signals (packets of data or data packets) used to transmit or receive information that is in the process of being transmitted. The term stream is used here to define raw, uncompressed content (video or audio) prior to being encoded into a wrapper or after being decoded from a wrapper.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Stream](../Submissions/DigitalVideo/Stream "Submissions:DigitalVideo/Stream") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AudioStream__ 
 (owl:Class) An audio stream is a stream where the carried data is audio content.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AudioStream](../Submissions/DigitalVideo/AudioStream "Submissions:DigitalVideo/AudioStream") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VideoStream__ 
 (owl:Class) A video stream is a stream where the carried data is video content.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VideoStream](../Submissions/DigitalVideo/VideoStream "Submissions:DigitalVideo/VideoStream") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SubtitleStream__ 
 (owl:Class) A subtitle stream is a stream where the carried data is subtitle content for a video.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SubtitleStream](../Submissions/DigitalVideo/SubtitleStream "Submissions:DigitalVideo/SubtitleStream") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Container__ 
 (owl:Class) A container or wrapper format is a metafile format whose specification describes how different elements of data and metadata coexist in a computer file. 
E.g. Matroska (MKV), MP4, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Container](../Submissions/DigitalVideo/Container "Submissions:DigitalVideo/Container") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Descriptor__ 
 (owl:Class) Descriptors are the various elements describing a digital video, a container, a stream or a codec.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[Descriptor](../Submissions/DigitalVideo/Descriptor "Submissions:DigitalVideo/Descriptor") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AnalogBroadcastStandard__ 
 (owl:Class) The video color encoding system, if the video originates from analog television broadcasts. 
E.g. NTSC, PAL, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AnalogBroadcastStandard](../Submissions/DigitalVideo/AnalogBroadcastStandard "Submissions:DigitalVideo/AnalogBroadcastStandard") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__AspectRatio__ 
 (owl:Class) The aspect ratio of an image describes the proportional relationship between its width and its height. It is commonly expressed as two numbers separated by a colon, as in 16:9. 
E.g. 16:9, 4:3, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[AspectRatio](../Submissions/DigitalVideo/AspectRatio "Submissions:DigitalVideo/AspectRatio") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__Bit Rate__ 
 (owl:Class) The bitrate is the data rate for a video or audio file. Video and audio data rates are given in bits per second. 
E.g. 2 MBits/s
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[BitRate](../Submissions/DigitalVideo/BitRate "Submissions:DigitalVideo/BitRate") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ChromaFormat__ 
 (owl:Class) The chroma subsampling type. Chroma subsampling is the practice of encoding images by implementing less resolution for chroma information than for luma information, taking advantage of the human visual system's lower acuity for color differences than for luminance. 
E.g. 4:2:0
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ChromaFormat](../Submissions/DigitalVideo/ChromaFormat "Submissions:DigitalVideo/ChromaFormat") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CodingStandard__ 
 (owl:Class) Also known as coding format or compression format. 
E.g. H.264/MPEG-4 AVC
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CodingStandard](../Submissions/DigitalVideo/CodingStandard "Submissions:DigitalVideo/CodingStandard") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ColourSpaceType__ 
 (owl:Class) A color space is a specific organization of colors. It allows for reproducible representations of color, in both analog and digital representations. A color space may be arbitrary, with particular colors assigned to a set of physical color swatches and corresponding assigned names or numbers. 
E.g. YUV, RGB, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ClourSpaceType](../Submissions/DigitalVideo/ClourSpaceType "Submissions:DigitalVideo/ClourSpaceType") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__CompressionType__ 
 (owl:Class) The type of video compression. 
E.g. lossy, lossless or uncompressed
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[CompressionType](../Submissions/DigitalVideo/CompressionType "Submissions:DigitalVideo/CompressionType") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__EmbeddingType__ 
 (owl:Class) The type of embedment used to attach a subtitle stream to a video. 
E.g. hard, prerendered, soft, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[EmbeddingType](../Submissions/DigitalVideo/EmbeddingType "Submissions:DigitalVideo/EmbeddingType") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FrameRate__ 
 (owl:Class) Frame rate, also known as frame frequency, is the frequency (rate) at which an imaging device produces unique consecutive images called frames. The term applies equally well to film and video cameras, computer graphics, and motion capture systems. Frame rate is most often expressed in frames per second (FPS) and is also expressed in progressive scan monitors as hertz (Hz). 
E.g. 60 FPS
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FrameRate](../Submissions/DigitalVideo/FrameRate "Submissions:DigitalVideo/FrameRate") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__FrameSize__ 
 (owl:Class) The dimensions of a video's frame. 
E.g. 1920 x 1080
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[FrameSize](../Submissions/DigitalVideo/FrameSize "Submissions:DigitalVideo/FrameSize") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__PlaybackDuration__ 
 (owl:Class) The duration of a video, video stream or audio stream. 
E.g. 22 minutes
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[PlaybackDuration](../Submissions/DigitalVideo/PlaybackDuration "Submissions:DigitalVideo/PlaybackDuration") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__RangeType__ 
 (owl:Class) The type of range a video is created for. 
E.g. broadcast range or full range
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[RangeType](../Submissions/DigitalVideo/RangeType "Submissions:DigitalVideo/RangeType") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SampleRate__ 
 (owl:Class) The audio sample rate is the number of samples of audio carried per second, measured in Hz or kHz (one kHz being 1 000 Hz). For example, 44 100 samples per second can be expressed as either 44 100 Hz, or 44.1 kHz.
 
 The video sample rate of a digital video format determines how often the light intensity of each video line is sampled.
 


 E.g. 96 kHz, 74.25MHz, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SampleRate](../Submissions/DigitalVideo/SampleRate "Submissions:DigitalVideo/SampleRate") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__ScanType__ 
 (owl:Class) Progressive or interlaced scan.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[ScanType](../Submissions/DigitalVideo/ScanType "Submissions:DigitalVideo/ScanType") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__SetOfStandards__ 
 (owl:Class) Sets of standards standardize the format of a video stream. 
E.g. BT.601 or BT.709
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SetOfStandards](../Submissions/DigitalVideo/SetOfStandards "Submissions:DigitalVideo/SetOfStandards") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__E.g. SubRip, SubViewer, etc.__ 
 (owl:Class) The file format of subtitles.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[SubtitleTextFormat](../Submissions/DigitalVideo/SubtitleTextFormat "Submissions:DigitalVideo/SubtitleTextFormat") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VideoCodecLevel__ 
 (owl:Class) A video codec level is a specified set of constraints that indicate a degree of required decoder performance for a profile. 
E.g. 4
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VideoCodecLevel](../Submissions/DigitalVideo/VideoCodecLevel "Submissions:DigitalVideo/VideoCodecLevel") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VideoCodecProfile__ 
 (owl:Class) The video codec profile is a set of capabilities and constraints apllied in the encoder. It allows the decoder to recognize the requirements to decode a specific stream. 
E.g. baseline profile, extended profile, main profile, high profile, etc.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VideoCodecProfile](../Submissions/DigitalVideo/VideoCodecProfile "Submissions:DigitalVideo/VideoCodecProfile") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VideoQualityMeasurement__ 
 (owl:Class) Measurement carried out according to the video quality metric.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VideoQualityMeasurement](../Submissions/DigitalVideo/VideoQualityMeasurement "Submissions:DigitalVideo/VideoQualityMeasurement") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__VideoQualityMetric__ 
 (owl:Class) Process or software used to measure the quality of a video. 
E.g. VQM
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[VideoQualityMetric](../Submissions/DigitalVideo/VideoQualityMetric "Submissions:DigitalVideo/VideoQualityMetric") 
 page_ 



[![Class](images/thumb/2/27/Class.gif/20px-Class.gif)](../Image/Class.gif "Class")
__YUVSampleRange__ 
 (owl:Class) YUV Sample Range 
E.g. 16-235
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[YUVSampleRange](../Submissions/DigitalVideo/YUVSampleRange "Submissions:DigitalVideo/YUVSampleRange") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasBitRate__ 
 (owl:ObjectProperty) Associates an audio or video stream with a bit rate.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasBitRate](../Submissions/DigitalVideo/hasBitRate "Submissions:DigitalVideo/hasBitRate") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__wrappedBy__ 
 (owl:ObjectProperty) Associates a digital video file with a container type.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[wrappedBy](../Submissions/DigitalVideo/wrappedBy "Submissions:DigitalVideo/wrappedBy") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasStream__ 
 (owl:ObjectProperty) Associates a digital video with a stream.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasStream](../Submissions/DigitalVideo/hasStream "Submissions:DigitalVideo/hasStream") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasAudioStream__ 
 (owl:ObjectProperty) Associates a digital video with an audio stream.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasAudioStream](../Submissions/DigitalVideo/hasAudioStream "Submissions:DigitalVideo/hasAudioStream") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVideoStream__ 
 (owl:ObjectProperty) Associates a digital video with a video stream.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVideoStream](../Submissions/DigitalVideo/hasVideoStream "Submissions:DigitalVideo/hasVideoStream") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSubtitleStream__ 
 (owl:ObjectProperty) Associates a digital video with a subtitle stream.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSubtitleStream](../Submissions/DigitalVideo/hasSubtitleStream "Submissions:DigitalVideo/hasSubtitleStream") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasCodingStandard__ 
 (owl:ObjectProperty) Associates a video or audio stream with a coding standard.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasCodingStandard](../Submissions/DigitalVideo/hasCodingStandard "Submissions:DigitalVideo/hasCodingStandard") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasRangeType__ 
 (owl:ObjectProperty) Associates a video stream with a range type.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasRangeType](../Submissions/DigitalVideo/hasRangeType "Submissions:DigitalVideo/hasRangeType") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVideoQualityMeasurement__ 
 (owl:ObjectProperty) Associates a video stream with a video quality measurement.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVideoQualityMeasurement](../Submissions/DigitalVideo/hasVideoQualityMeasurement "Submissions:DigitalVideo/hasVideoQualityMeasurement") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasChromaFormat__ 
 (owl:ObjectProperty) Associates a video stream with a chroma format.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasChromaFormat](../Submissions/DigitalVideo/hasChromaFormat "Submissions:DigitalVideo/hasChromaFormat") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasEmbeddingType__ 
 (owl:ObjectProperty) Associates a subtitle stream with an embedding type.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasEmbeddingType](../Submissions/DigitalVideo/hasEmbeddingType "Submissions:DigitalVideo/hasEmbeddingType") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasAspectRatio__ 
 (owl:ObjectProperty) Associates a video stream with an aspect ratio.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasAspectRatio](../Submissions/DigitalVideo/hasAspectRatio "Submissions:DigitalVideo/hasAspectRatio") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSubtitleTextFormat__ 
 (owl:ObjectProperty) Associates a subtitle stream with a subtitle text format.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSubtitleTextFormat](../Submissions/DigitalVideo/hasSubtitleTextFormat "Submissions:DigitalVideo/hasSubtitleTextFormat") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVideoQualityMetric__ 
 (owl:ObjectProperty) Associates a video stream with a video quality metric.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVideoQualityMetric](../Submissions/DigitalVideo/hasVideoQualityMetric "Submissions:DigitalVideo/hasVideoQualityMetric") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasCompressionType__ 
 (owl:ObjectProperty) Associates a video or audio codec with a compression type.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasCompressionType](../Submissions/DigitalVideo/hasCompressionType "Submissions:DigitalVideo/hasCompressionType") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasScanType__ 
 (owl:ObjectProperty) Associates a video stream with a scan type.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasScanType](../Submissions/DigitalVideo/hasScanType "Submissions:DigitalVideo/hasScanType") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVideoCodecProfile__ 
 (owl:ObjectProperty) Associates a video codec with a video codec profile.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVideoCodecProfile](../Submissions/DigitalVideo/hasVideoCodecProfile "Submissions:DigitalVideo/hasVideoCodecProfile") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasColourSpaceType__ 
 (owl:ObjectProperty) Associates a video stream with a colour space type.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasColourSpaceType](../Submissions/DigitalVideo/hasColourSpaceType "Submissions:DigitalVideo/hasColourSpaceType") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasFrameSize__ 
 (owl:ObjectProperty) Associates a video stream with a frame size.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasFrameSize](../Submissions/DigitalVideo/hasFrameSize "Submissions:DigitalVideo/hasFrameSize") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSetOfStandards__ 
 (owl:ObjectProperty) Associates a video stream with a set of standards.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSetOfStandards](../Submissions/DigitalVideo/hasSetOfStandards "Submissions:DigitalVideo/hasSetOfStandards") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__processedBy__ 
 (owl:ObjectProperty) Associates a stream with a codec.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[processedBy](../Submissions/DigitalVideo/processedBy "Submissions:DigitalVideo/processedBy") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasAnalogBroadcastStandard__ 
 (owl:ObjectProperty) Associates a digital video with an analog broadcast standard.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasAnalogBroadcastStandard](../Submissions/DigitalVideo/hasAnalogBroadcastStandard "Submissions:DigitalVideo/hasAnalogBroadcastStandard") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasVideoCodecLevel__ 
 (owl:ObjectProperty) Associates a video codec with a video codec level.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasVideoCodecLevel](../Submissions/DigitalVideo/hasVideoCodecLevel "Submissions:DigitalVideo/hasVideoCodecLevel") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasFrameRate__ 
 (owl:ObjectProperty) Associates a video stream with a frame rate.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasFrameRate](../Submissions/DigitalVideo/hasFrameRate "Submissions:DigitalVideo/hasFrameRate") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasPlaybackDuration__ 
 (owl:ObjectProperty) Associates a digital video, a video stream or an audio stream with a playback duration.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasPlaybackDuration](../Submissions/DigitalVideo/hasPlaybackDuration "Submissions:DigitalVideo/hasPlaybackDuration") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasYUVSampleRange__ 
 (owl:ObjectProperty) Associates a video stream with a YUV sample range.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasYUVSampleRange](../Submissions/DigitalVideo/hasYUVSampleRange "Submissions:DigitalVideo/hasYUVSampleRange") 
 page_ 



[![ObjectProperty](images/thumb/c/c3/ObjectProperty.gif/20px-ObjectProperty.gif)](../Image/ObjectProperty.gif "ObjectProperty")
__hasSampleRate__ 
 (owl:ObjectProperty) Associates a video stream or audio stream with a sample rate.
 
[![](images/thumb/8/87/ArrowRight.gif/11px-ArrowRight.gif)](../Image/ArrowRight.gif "ArrowRight.gif")
_[hasSampleRate](../Submissions/DigitalVideo/hasSampleRate "Submissions:DigitalVideo/hasSampleRate") 
 page_ 


# 

 Additional information



# 

 Scenarios




__Scenarios about DigitalVideo__ 


 No scenario is added to this Content OP.
 




# 

 Reviews




__Reviews about DigitalVideo__ 


 There is no review about this proposal.
This revision (revision ID
 __13288__ 
 ) takes in account the reviews: none
 



 Other info at
 [evaluation tab](http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DigitalVideo&action=evaluation "http://ontologydesignpatterns.org/wiki/index.php?title=Submissions:DigitalVideo&action=evaluation") 





  





# 

 Modeling issues




__Modeling issues about DigitalVideo__ 


 There is no Modeling issue related to this proposal.
 




  





# 

 References


* The homepage of the PERICLES project that supported the development of this ODP. [Project Home Page](http://www.pericles-project.eu/ "http://www.pericles-project.eu/")  | [reference page](../Community/References/PERICLES_project_homepage "Community:References/PERICLES project homepage")* The paper presenting the ODP that was accepted for publication in the WOP'15 proceedings. [Workshop publication](http://ceur-ws.org/Vol-1461/WOP2015_pattern_abstract_4.pdf "http://ceur-ws.org/Vol-1461/WOP2015_pattern_abstract_4.pdf")  | [reference page](../Community/References/An_Ontology_Design_Pattern_for_Digital_Video "Community:References/An Ontology Design Pattern for Digital Video")


  






|  |  Submission to event [WOP:2015](../WOP/2015 "WOP:2015")  |
| --- | --- |