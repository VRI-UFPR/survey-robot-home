# 1. Software

|                    | AraraBots-2019   | AraraBots-2022 |
| ---                | ---              | ---            |
| Operating system   | Debian 9         | Ubuntu 20.04   |
| Middleware         | ROS Kinetic      | ROS Noetic     |
| Navigation         | RTAB-Map         | RTAB-Map       |
| Localization       | RTAB-Map         | RTAB-Map       |
| Mapping            | RTAB-Map         | RTAB-Map       |
| Object recognition | OpenCV+RetinaNet | MediaPipe      |
| Face detection     | ---              | ---            |
| Face recognition   | OpenCV           | Face Recogn.   |
| Human detection    | ---              | ---            |
| Gesture recogn.    | ---              | ---            |
| Speech synthesis   | ---              | ---            |
| Speech recognition | ---              | DeepSpeech     |
| NLP                | ---              | RoBERTa        |

|                    | BahiaRT-2019 | BahiaRT-2022                | BahiaRT-2023   |
| ---                | ---          | ---                         | ---            |
| Operating system   | ---          | ---                         | ---            |
| Middleware         | ROS          | ROS                         | ROS            |
| Navigation         | ---          | Voronoi + D* Lite algorithm | Voronoi + D* Lite algorithm |
| Localization       | AMCL         | AMCL                        | AMCL           |
| Mapping            | ---          | Hector mapping              | Hector mapping |
| Object recognition | ---          | YOLO                        | YOLO v5        |
| Face detection     | HaarCascade  | OpenCV library              | HaarCascade    |
| Face recognition   | ---          | ---                         | DLib+FaceNet   |
| Human detection    | ---          | ---                         |                |
| Gesture recogn.    | ---          | ---                         | ---            |
| Speech synthesis   | Festival     | ROS Sound Play              | ---            |
| Speech recognition | PocketSphinx | Vosk and Kaldi library      | Google Speech  |
| NLP                | ---          | ---                         | ---            |

|                    |  FBot-2019           | FBot-2023          |
| ---                |  ---                 | ---                |
| Operating system   |  ---                 | ---                |
| Middleware         |  ROS                 | ROS Noetic         |
| Navigation         |  ---                 | ---                |
| Localization       |  AMCL                | AMCL               |
| Mapping            |  RBPF                | RBPF               |
| Object recognition |  YOLO v3             | YOLO v8            |
| Face detection     |  OpenCV              | ---                |
| Face recognition   |  SVM                 | Openface           |
| Human detection    |  YOLO v3             | DeepSORT(tracking) |
| Gesture recogn.    |  ---                 | ---                |
| Speech synthesis   |  ---                 | ---                |
| Speech recognition |  Google Cloud Speech | Whisper            |
| NLP                |  ---                 | Langchain          |

|                    | Pinguim-2019            | Pinguim-2022                     | Pinguim-2023         |
| ---                | ---                     | ---                              | ---                  |
| Operating system   | Ubuntu 16               | Ubuntu 16                        | Ubuntu 20            |
| Middleware         | ROS Kinetic             | ROS Kinetic                      | ROS Noetic           |
| Navigation         | ---                     | ROS Navigation Stack             | ROS Navigation Stack |
| Localization       | AMCL                    | AMCL                             | AMCL                 |
| Mapping            | ---                     | Gmapping ROS                     | Gmapping ROS         |
| Object recognition | YOLO                    | ResNet 18                        | ResNet 18            |
| Face detection     | ---                     | O-Net                            | OpenCV + MediaPipe   |
| Face recognition   | ---                     | MobileNet                        | OpenCV + MediaPipe   |
| Human detection    | ---                     | ---                              | ---                  |
| Gesture recogn.    | ---                     | OpenNI and Nite                  | OpenNI and Nite      |
| Speech synthesis   | PocketSphinx            | Google’s voice synthesizer       | Nvidia NeMo          |
| Speech recognition | Google Cloud Speech     | Vosk + Google Speech Recognition | Whisper              |
| NLP                | ---                     | ---                              | ---                  |

|                    | PQMEC-2019              | PQMEC-2022                  | PQMEC-2023              |
| ---                | ---                     | ---                         | ---                     |
| Operating system   | Ubuntu 18.04            | Ubuntu 18.04                | Ubuntu 20.04            |
| Middleware         | ROS Melodic             | ROS Melodic                 | ROS 2 Foxy              |
| Navigation         | ROS Navigation Stack    | ROS Navigation Stack        | ROS 2 Navigation Stack  |
| Localization       | AMCL                    | AMCL                        | AMCL                    |
| Mapping            | Gmapping                | Gmapping                    | Gmapping                |
| Object recognition | SSD MobileNet V2        | YOLOv4 tiny                 | YOLOv8                  |
| Face detection     | Haar Cascades           | YOLOv4 tiny                 | YOLOv8                  |
| Face recognition   | EigenFaces              | Eigenfaces                  | EigenFaces              |
| Human detection    | OpenPose                | OpenPose                    | OpenPose                |
| Gesture recogn.    | OpenPose                | OpenPose                    | OpenPose                |
| Speech synthesis   | Festival                | Google Cloud Text-to-Speech | FastSpeech and HiFi-Gan |
| Speech recognition | Google Cloud Speech     | Google Cloud Speech-to-Text | Conformer-CTC           |
| NLP                | Rasa NLU                | Rasa NLU                    | Llama 2                 |


|                    | RoboFEI@Home-2019                        | RoboFEI@Home-2022                      | RoboFEI@Home-2023                    |
| ---                | ---                                      | ---                                    | ---                                  |
| Operating system   | Ubuntu 16.04                             | Ubuntu 20.04                           | Ubuntu 20.04                         |
| Middleware         | ROS Kinetic                              | ROS Noetic                             | ROS Noetic                           |
| Navigation         | ---                                      | ---                                    | ---                                  |
| Localization       | ---                                      | ---                                    | ---                                  |
| Mapping            | ---                                      | SLAM                                   | ---                                  |
| Object recognition | SIFT+FLANN or MobileNet+SSD              | MobileNet v2 + SSD on Synthetic Data   | MobileNet v2 + SSD on Synthetic Data |
| Face detection     | Haar cascades                            | ---                                    | Haar cascades                        |
| Face recognition   | LBP Algorithm                            | ---                                    | LBP Algorithm                        |
| Human detection    | PCL                                      | OpenPose                               | OpenPose                             |
| Gesture recogn.    | OpenNI                                   | Wave! and OpenNI                       | Wave! and OpenNI                     |
| Speech synthesis   | Festival                                 | Flite or GTTs                          | Flite or GTTs                        |
| Speech recognition | Dragonfly and Windows Speech Recognition | DeepSpeech + Google Speech Recognition | DeepSpeech                           |
| NLP                | ---                                      | ---                                    | ---                                  |

|                    | UTBots-2019             | UTBots-2022            | UTBots-2023            |
| ---                | ---                     | ---                    | ---                    |
| Operating system   | Ubuntu 16.04            | Ubuntu 18              | Ubuntu 20.04           |
| Middleware         | ROS                     | ROS Melodic            | ROS Noetic and Melodic |
| Navigation         | ---                     | ROS Navigation Stack   | ---                    |
| Localization       | AMCL                    | ---                    | AMCL                   |
| Mapping            | SLAM EKF                | ---                    | ---                    |
| Object recognition | Blob detection          | YOLOv3                 | YOLOv3                 |
| Face detection     | ---                     | ---                    | ---                    |
| Face recognition   | ---                     | ---                    | KNN                    |
| Human detection    | OpenNI                  | YOLOv3                 | YOLOv3                 |
| Gesture recogn.    | ---                     | ---                    | MediaPipe              |
| Speech synthesis   | PocketSphinx-ESpeak     | ESpeak ROS             | Mimic3                 |
| Speech recognition | Google Cloud Speech     | ---                    | Whisper                |
| NLP                | ---                     | ---                    | ---                    |

|                    | Warthog-2019            | Warthog-2022 | Warthog-2023 | 
| ---                | ---                     | ---          | ---          |
| Operating system   | ---                     | ---          | ---          |
| Middleware         | ROS                     | ROS          | ROS          |
| Navigation         | A* algorithm            | ---          | WRNavigation |
| Localization       | AMCL                    | ---          | WRNavigation |
| Mapping            | Gmapping                | ---          | WRNavigation |
| Object recognition | Faster R-CNN            | ---          | WRVision     |
| Face detection     | OpenFace                | ---          | WRVision     |
| Face recognition   | ---                     | ---          | WRVision     |
| Human detection    | ---                     | ---          | WRFollow     |
| Gesture recogn.    | ---                     | ---          | WRFollow     |
| Speech synthesis   | LianeTTS                | ---          | WRSpeech     |
| Speech recognition | DeepSpeech              | ---          | WRParser     |
| NLP                | ---                     | ---          | WRParser     | 



# 2. Hardware

|                | AraraBots-2019                 | AraraBots-2022                 |
| ---            | ---                            | ---                            |
| Batteries      | 3 Makita Lithium-Ion 18V-3.0Ah | 3 Makita Lithium-Ion 18V-3.0Ah |
| Base Motors    | BLHM015K-30                    | ---                            | 
| Manipulators   | ---                            | ---                            |
| Microphone     | 1 Microphone                   | ---                            |
| Display        | Galaxy Tab 4                   | Galaxy Tab 4                   |
| RGB-D Camera   | Kinect                         | Kinect                         |
| RGB Camera     | LifeCam 720p                   | LifeCam 720p                   |
| Speaker        | 2 Speakers                     | 2 Speakers                     |
| IMU            | ---                            | ---                            |
| LiDAR          | ---                            | ---                            |
| Emb. System    | Lenovo Intel i5 with 8GB RAM   | Lenovo Intel i5 with 8GB RAM   |

|                 | BahiaRT-2019                                          | BahiaRT-2023                       |
| ---             | ---                                                   | ---                                |
| Batteries       | 3 Makita Lithium-Ion 18V-3.0Ah                        | 3 batteries 11.1v and 2800 mAh     | 
| Base Motors     | 2 Motors IG32P 24VDC + Encoder                        | ---                                | 
| Manipulators    | 5 Dynamixel-ax-12A;  One ArbotiX-M; Maximum load: 1kg | ---                                | 
| Microphone      | 1 Rode Videomic Pro                                   | 1 Rode VideoMic Go                 | 
| Display         | Motorola tablet                                       | ---                                | 
| RGB-D Camera    | Kinect                                                | ---                                | 
| RGB Camera      | 2 Webcam HD-3000                                      | 1 Webcam FullHD                    | 
| Speaker         | ---                                                   | ---                                |
| IMU             | ---                                                   | ---                                | 
| LiDAR           | RPLiDAR 360                                           | RPLiDAR 360                        | 
| Emb. System     | Lenovo Intel i5 with 8GB RAM                          | Notebook Dell Inspiron 15R-4470 i7 | 

|                 |  FBot-2019                                        | FBot-2022 | FBot-2023                                       |
| ---             |  ---                                              | ---       | ---                                             |
| Batteries       | Bateria PowerTek 12v - End 11A                    |           | ---                                             |
| Base Motors     | PatrolBots                                        |           | PatrolBots                                      |
| Manipulators    | 5 DOF arm                                         |           | 5 DOF Arm                                       |
| Microphone      | 1 Rode VideoMic Pro                               |           | ---                                             | 
| Display         | ---                                               |           | ---                                             |
| RGB-D Camera    | Kinect v2                                         |           | Intel D435i                                     |
| RGB Camera      | ---                                               |           | ---                                             |
| Speaker         | ---                                               |           | ---                                             |
| IMU             | ---                                               |           | ---                                             |
| LiDAR           | SICK LMS-100 and Hokuyo URG-04LX-UG01             |           | SICK LMS-100 and Hokuyo URG-04LX                |
| Emb. System     | Intel N509516GB+512GB, Intel NUC and Jetson TX2   |           | Intel NUC, Jetson TX2 and notebook i7 8705G 8gb | 

|                 | Pinguim-2019              | Pinguim-2023        |
| ---             | ---                       | ---                 |
| Batteries       | Wheelchair battery        | Wheelchair bat.     |
| Base Motors     | ---                       | ---                 |
| Manipulators    | ---                       | ---                 |
| Microphone      | ---                       | ---                 |
| Display         | ---                       | ---                 |
| RGB-D Camera    | Kinect                    | Kinect              |
| RGB Camera      | Kinect                    | Kinect              |
| Speaker         | ---                       | ---                 |
| IMU             | ---                       | ---                 |
| LiDAR           | YDLiDAR X4                | YDLiDAR X4          |
| Emb. System     | Intel Core T6670 2 GB RAM | ---                 |

|                 | PQMEC-2019                  |  PQMEC-2023                     | 
| ---             | ---                         | ---                             |
| Batteries       | ---                         | ---                             |
| Base Motors     | 4x Pololu XYZ               | 4x Hoverboard Wheel Motor 6.5'' |
| Manipulators    | XYZrobot 6 DOF              | Trossen 6 DOF Arm               |
| Microphone      | Rode Videomic Go            | Rode Videomic Go                |
| Display         | Galaxy Tab S3               |  Galaxy Tab S3                  |
| RGB-D Camera    | Kinect                      | Intel D435i                     |
| RGB Camera      | Logitech Pro C920           | Intel D435i                     |
| Speaker         | JBL Charge 3                | JBL Charge 3                    |
| IMU             | BN0055                      | Intel D435i                     |
| LiDAR           | RPLiDAR A2                  | RPLiDAR A2                      |
| Emb. System     | Jetson TX2                  |Jetson Xavier and Intel NUC      |

|                 | RoboFEI-2019       | RoboFEI-2023      | 
| ---             | ---                | ---               |
| Batteries       | ---                | ---               |
| Base Motors     | PeopleBot          | PeopleBot         |
| Manipulators    | 7 DOF Arm          | 6 DOF Arm         |
| Microphone      | 2 Rode VideoMic Go | 2 HyperX QuadCast |
| Display         | Apple Ipad 2       | Apple Ipad 2      |
| RGB-D Camera    | Kinect             | Kinect            |
| RGB Camera      | Logitech c920      | Logitech c920     |
| Speaker         | ---                | JBL Charge 5      |
| IMU             | ---                | ---               |
| LiDAR           | Hokuyo UTM-30LX-EW | Hokuyo URG-04LX   |
| Emb. System     | Intel NUC i5 5250U | ---               |

|                 |  UTBots@Apollo-2019              | UTBots@Apollo-2023   |
| ---             |  ---                             | ---                  |
| Batteries       |  3 x 12 volts standard batteries | ---                  |
| Base Motors     |  Pioneer LX                      | Pioneer LX           |
| Manipulators    |  ---                             | ORCA Robotic Arm     |
| Microphone      |  ---                             | ---                  |
| Display         |  T-7305 tablet                   | ---                  |
| RGB-D Camera    |  Kinect                          | Kinect               |
| RGB Camera      |  ---                             | ---                  |
| Speaker         |  ---                             | ---                  |
| LiDAR           |  Hokuyo URG-04LX                 | YDLiDAR X4           |

|                 | Warthog-2019      |  Warthog-2023                   |
| ---             | ---               | ---                             |
| Batteries       | ---               | ---                             |
| Base Motors     | Pioneer P3-DX     | Pioneer P3-DX                   |
| Manipulators    | ---               | ---                             |
| Microphone      | ---               | Microphone with noise canceling |
| Display         | ---               | ---                             |
| RGB-D Camera    | Kinect 2          | Kinect 2                        |
| RGB Camera      | Kinect 2          | Kinect 2                        |
| Speaker         | ---               | External speaker                |
| LiDAR           | Hokuyo            | Hokuyo                          |