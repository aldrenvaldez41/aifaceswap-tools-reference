# aifaceswap-tools-reference
Complete reference guide for all AI tools available on AIFaceSwap platform, including which tools support API access for integration and skill creation.
# AIFaceSwap Tools Reference Guide

**Complete reference guide for all AI tools available on AIFaceSwap platform, including which tools support API access for integration and skill creation.**

---

## Table of Contents
1. [AI Face Swap Tools](#ai-face-swap-tools)
2. 2. [AI Video Tools](#ai-video-tools)
   3. 3. [AI Video Effects](#ai-video-effects)
      4. 4. [AI Image Generator](#ai-image-generator)
         5. 5. [AI Image Editor](#ai-image-editor)
            6. 6. [AI Photo Effects](#ai-photo-effects)
               7. 7. [AI Audio Tools](#ai-audio-tools)
                  8. 8. [Other Tools](#other-tools)
                     9. 9. [API Support Summary](#api-support-summary)
                       
                        10. ---
                       
                        11. ## AI Face Swap Tools
                       
                        12. | # | Tool Name | Status |
                        13. |---|-----------|--------|
                        14. | 1 | Face Swap | ✓ |
                        15. | 2 | Video Face Swap | ✓ |
                        16. | 3 | Multiple Face Swap | ✓ |
                        17. | 4 | Gif Face Swap | ✓ |
                        18. | 5 | Batch Face Swap | ✓ |
                        19. | 6 | Batch Video Face Swap | ✓ |
                        20. | 7 | Template for Faceswap | ✓ |
                        21. | 8 | Gender Swap | ✓ |
                        22. | 9 | Celebrity Face Swap | ✓ |
                        23. | 10 | Face Swap Meme Maker | ✓ |
                        24. | 11 | AI Face Morph | ✓ |
                        25. | 12 | Head Swap AI | ✓ |
                        26. | 13 | Character Swap | ✓ |
                        27. | 14 | Animal Face Swap | ✓ |
                        28. | 15 | **AI Face Swap API** | **API ✓** |
                       
                        29. ---
                       
                        30. ## AI Video Tools
                       
                        31. Image to Video, Text to Video, Vidu Q3, Hailuo 2.3, Wan 2.6, Kling 2.6, Seedance AI Video Generator, Veo 3.1, Sora 2, Sora 2 Watermark Remover, AI Motion Transfer, AI Mimic Motion, Frame To Video, AI Reference to Video, AI Video Enhancer, AI Talking Photo, AI Lip Sync Generator, Live Portrait AI, Video Watermark Remover, Video Background Remover, AI Video Extender, Video to Video, AI Pet Talking
                       
                        32. **Total: 23+ tools**
                       
                        33. ---
                       
                        34. ## AI Video Effects
                       
                        35. AI Christmas Video Maker, AI Kissing Video Generator, AI Hug Video Generator, AI Bikini Video Generator, AI Twerk Generator, Ghibli AI Video Generator, AI Chibi Video Filter, AI Mermaid Filter, AI Bouncing Breast Generator, AI Dance Generator, AI Emotion Video Generator, AI Morph Video, AI Hair Gradient Video, AI Interactive Video, AI Bloom Effect Video Filter, AI Inflate Effect Video Filter, AI Flying Video Generator, Beast Companion Effect, AI Body Shake Video Generator, AI Earth Zoom Out Generator, AI Pole Dance Generator, AI Muscle Video Generator, Shake It Dance Generator, AI Beast Chase Generator
                       
                        36. **Total: 25+ tools**
                       
                        37. ---
                       
                        38. ## AI Image Generator
                       
                        39. Seedream 4.0, Text to Image, AI Clothes Changer, AI Image Editor, AI Headshot Generator, AI Hairstyle Changer, AI Sticker Generator, Image to Image, AI Body Generator, AI Image Inpainting, AI Breast Enlarger, AI Tattoo Generator, AI Face Cut out, AI Clothes Remover, Nano Banana (AI, Pro, Prompt versions)
                       
                        40. **Total: 15+ tools**
                       
                        41. ---
                       
                        42. ## AI Image Editor
                       
                        43. AI Face Enhancer, AI Image Upscaler, AI Photo Enhancer, AI Image Extender, AI Watermark Remover, AI Background Remover, AI Face Editor, AI Magic Eraser
                       
                        44. **Total: 8 tools**
                       
                        45. ---
                       
                        46. ## AI Photo Effects
                       
                        47. Beardless Filter, Bald Filter, AI Age Filter, AI Wrinkle Remover, AI Halloween Generator, AI Skin Color Changer, Celebrity Selfie Generator, Polaroid Duo Selfie
                       
                        48. **Total: 8 tools**
                       
                        49. ---
                       
                        50. ## AI Audio Tools
                       
                        51. | Tool Name |
                        52. |-----------|
                        53. | AI Music Generator |
                        54. | AI Voice Cloning |
                        55. | Extract Audio from Video |
                        56. | YouTube to MP3 |
                        57. | YouTube to MP4 |
                        58. | YouTube Thumbnail Downloader |
                        59. | YouTube Playlist Downloader |
                        60. | Mic Test |
                        61. | Text to Speech |
                        62. | Speech to Speech |
                       
                        63. **Total: 10 tools**
                       
                        64. ---
                       
                        65. ## Other Tools
                       
                        66. Image To Prompt, AI Manga Translator, AI Signature Generator, Image Converter Online, AI Attractiveness Test, AI Graffiti Letter Generator, AI Brat Generator, AI Meme Generator, AI Palm Reader, AI Face Reader, Video To Gif, Video To Webp
                       
                        67. **Total: 12 tools**
                       
                        68. ---
                       
                        69. ## API Support Summary
                       
                        70. ### ✓ Tools with API Access
                       
                        71. Currently, **only Face Swap related APIs** are available:
                       
                        72. 1. **Face Swap API**
                            2.    - Endpoint: `POST api/aifaceswap/v1/faceswap`
                                  -    - Cost: 2 credits
                                       -    - Parameters: source_image, face_image, webhook (optional)
                                        
                                            - 2. **Extract Faces API**
                                              3.    - Endpoint: `POST api/aifaceswap/v1/extract_face`
                                                    -    - Cost: 2 credits
                                                         -    - Parameters: img
                                                              -    - Purpose: Extract all faces from images for multiple face swap
                                                               
                                                                   - 3. **Multiple Face Swap API**
                                                                     4.    - Endpoint: `POST api/aifaceswap/v1/multi_faceswap`
                                                                           -    - Cost: 5 credits
                                                                                -    - Parameters: source_image, face_image (array), index (array), webhook (optional)
                                                                                     -    - Max faces: Unlimited in image
                                                                                      
                                                                                          - 4. **Video Face Swap API**
                                                                                            5.    - Endpoint: `POST api/aifaceswap/v1/video_faceswap`
                                                                                                  -    - Cost: 2 credits/sec (no enhance), 4 credits/sec (1080p), 6 credits/sec (2k)
                                                                                                       -    - Parameters: source_video, face_image, duration, enhance (0-2), webhook (optional)
                                                                                                        
                                                                                                            - 5. **Extract Faces From Video Frame API**
                                                                                                              6.    - Endpoint: `POST api/aifaceswap/v1/extract_base64_face`
                                                                                                                    -    - Cost: 2 credits
                                                                                                                         -    - Parameters: base64_img
                                                                                                                              -    - Purpose: Extract face points from video frames for multiple video face swap
                                                                                                                               
                                                                                                                                   - 6. **Multiple Video Face Swap API**
                                                                                                                                     7.    - Endpoint: `POST api/aifaceswap/v1/multi_video_faceswap`
                                                                                                                                           -    - Cost: (face_count + 1) * 2 credits/sec (no enhance)
                                                                                                                                                -    - Cost: (face_count + 2) * 2 credits/sec (1080p)
                                                                                                                                                     -    - Cost: (face_count + 3) * 2 credits/sec (2k)
                                                                                                                                                          -    - Parameters: source_video, ref_info (array), duration, enhance (0-2), webhook (optional)
                                                                                                                                                               -    - Max faces: 3
                                                                                                                                                                
                                                                                                                                                                    - ### Authentication
                                                                                                                                                                
                                                                                                                                                                    - All API calls require: `Authorization: Bearer your_api_key`
                                                                                                                                                                
                                                                                                                                                                    - - Obtain API keys from: API Management Page (requires login)
                                                                                                                                                                      - - API access is currently limited to VIP users with credits/coins
                                                                                                                                                                        - - Free tier API access: Not available
                                                                                                                                                                         
                                                                                                                                                                          - ### Important Notes
                                                                                                                                                                         
                                                                                                                                                                          - - Videos/images must be publicly accessible CDN URLs
                                                                                                                                                                            - - API does not provide video uploading or cropping services
                                                                                                                                                                              - - Use ffmpeg or similar tools for video processing
                                                                                                                                                                                - - Webhook callbacks return results when processing is complete
                                                                                                                                                                                  - - Response format: JSON with code, data, extra_data, and message
                                                                                                                                                                                   
                                                                                                                                                                                    - ---
                                                                                                                                                                                    
                                                                                                                                                                                    ## Summary Statistics
                                                                                                                                                                                    
                                                                                                                                                                                    | Category | Count | API Support |
                                                                                                                                                                                    |----------|-------|-------------|
                                                                                                                                                                                    | Face Swap Tools | 15 | Yes ✓ |
                                                                                                                                                                                    | Video Tools | 23+ | No |
                                                                                                                                                                                    | Video Effects | 25+ | No |
                                                                                                                                                                                    | Image Generator | 15+ | No |
                                                                                                                                                                                    | Image Editor | 8 | No |
                                                                                                                                                                                    | Photo Effects | 8 | No |
                                                                                                                                                                                    | Audio Tools | 10 | No |
                                                                                                                                                                                    | Other Tools | 12 | No |
                                                                                                                                                                                    | **TOTAL** | **130+** | **6 APIs** |
                                                                                                                                                                                    
                                                                                                                                                                                    ---
                                                                                                                                                                                    
                                                                                                                                                                                    ## Usage for Skill Creation & Prompts
                                                                                                                                                                                    
                                                                                                                                                                                    This reference guide is organized to help you:
                                                                                                                                                                                    
                                                                                                                                                                                    - **Identify available tools** quickly by category
                                                                                                                                                                                    - - **Find API-compatible tools** for integration with bots/automation
                                                                                                                                                                                      - - **Reference API endpoints** for development
                                                                                                                                                                                        - - **Check pricing** for API cost estimation
                                                                                                                                                                                          - - **Plan features** that leverage AIFaceSwap capabilities
                                                                                                                                                                                           
                                                                                                                                                                                            - ### API Development Notes
                                                                                                                                                                                           
                                                                                                                                                                                            - - All APIs use RESTful architecture (POST method)
                                                                                                                                                                                              - - Webhook support enables asynchronous processing
                                                                                                                                                                                                - - Base URL: `https://aifaceswap.io/`
                                                                                                                                                                                                  - - Response codes: 200 (success), error codes for failures
                                                                                                                                                                                                    - - Currently focusing on face manipulation APIs only
                                                                                                                                                                                                     
                                                                                                                                                                                                      - ---
                                                                                                                                                                                                      
                                                                                                                                                                                                      *Last Updated: February 28, 2026*
                                                                                                                                                                                                      *Data Source: AIFaceSwap Platform (aifaceswap.io)*
