# Graphics programming resources

**A searchable list of graphics programming resources to help with programming.**

# Intro
This document contains a large list of graphics programming resources I found from some googling. This document is incredibly useful when conducting research before implementing a graphics technique in code as:
- There are so many unique ways different tech demos and games tackle the same graphics problems. 
- Many techniques are also buried in the web, so having a consolidated searchable list helps immensely.

# Possible future improvements
- Combine similar headings from different repos together
- Use git submodules and file embedding to scrape up to date information

# Table of contents
1. [Kosua](#kosua)
2. [Graphics programming virtual meetup (GPVM)](#gpvm)
3. [Books](#books2)
4. [Real-time rendering portal](#real-time-rendering-portal)

# Kosua <a id="kosua"></a>
https://gist.github.com/kosua20/a337366c6fd2871f73022da8e69e8b76

## Table of Contents
- [Render](#render)
  - [Animation](#animation)
  - [Antialiasing](#antialiasing)
  - [Blending](#blending)
  - [Compression](#compression)
  - [Dithering](#dithering)
  - [Dof](#dof)
  - [Geometry](#geometry)
  - [Gpu](#gpu)
  - [Hdr](#hdr)
  - [Lens flare](#lens-flare)
  - [Lighting](#lighting)
  - [Lod](#lod)
  - [Motion blur](#motion-blur)
  - [Normal mapping](#normal-mapping)
  - [Path tracing](#path-tracing)
  - [Pipeline](#pipeline)
  - [Point cloud](#point-cloud)
  - [Postprocess](#postprocess)
  - [Procedural](#procedural)
  - [Rasterization](#rasterization)
  - [Ray tracing](#ray-tracing)
  - [Raymarching](#raymarching)
  - [Sampling](#sampling)
  - [Screenspace](#screenspace)
  - [Sdf](#sdf)
  - [Shader](#shader)
  - [Shadow](#shadow)
  - [Snow](#snow)
  - [Stereogram](#stereogram)
  - [Swapchain](#swapchain)
  - [Vfx](#vfx)
  - [Visibility](#visibility)
  - [Volumetric](#volumetric)
  - [Water](#water)
- [Gpu](#gpu)
  - [Debug](#debug)
  - [Dx12](#dx12)
  - [Hardware](#hardware)
  - [Maths](#maths)
  - [Performance](#performance)
  - [Pipeline](#pipeline)
  - [Security](#security)
  - [Shader](#shader)
  - [Thread](#thread)
  - [Vulkan](#vulkan)
  - [Webgpu](#webgpu)
- [Prog](#prog)
  - [Arm](#arm)
  - [Assembly](#assembly)
  - [Build](#build)
  - [Demoscene](#demoscene)
  - [Font](#font)
  - [Fun](#fun)
  - [Hardware](#hardware)
  - [Kinect](#kinect)
  - [Memory](#memory)
  - [Multithread](#multithread)
  - [Reverse engineering](#reverse-engineering)
  - [Security](#security)
  - [Tutorial](#tutorial)
- [Retro](#retro)
  - [Dreamcast](#dreamcast)
  - [Glide](#glide)
  - [Nintendo](#nintendo)
  - [Sony](#sony)
  - [Techno](#techno)
  - [Vectrex](#vectrex)
  - [Video](#video)

## Render

### Animation

#### Skinning
- https://blog.traverseresearch.nl/ray-tracing-animated-crowds-bc0e775c74ad  

### Antialiasing
- http://advances.realtimerendering.com/s2017/DecimaSiggraph2017.pdf  
- https://bartwronski.com/2014/03/15/temporal-supersampling-and-antialiasing/  
- http://behindthepixels.io/assets/files/TemporalAA.pdf  
- https://blog.codinghorror.com/fast-approximate-anti-aliasing-fxaa/  
- https://community.arm.com/graphics/b/blog/posts/temporal-anti-aliasing  
- https://de45xmedrsdbp.cloudfront.net/Resources/files/TemporalAA_small-59732822.pdf  
- http://developer.download.nvidia.com/assets/gamedev/files/sdk/11/FXAA_WhitePaper.pdf  
- http://developer.download.nvidia.com/gameworks/events/GDC2016/msalvi_temporal_supersampling.pdf  
- http://hacksoflife.blogspot.com/2011/04/so-many-aa-techniques-so-little-time.html  
- https://juandiegomontoya.github.io/porting_fsr2.html  
- http://media.steampowered.com/apps/valve/2015/Alex_Vlachos_Advanced_VR_Rendering_GDC2015.pdf  
- https://software.intel.com/en-us/articles/dynamic-resolution-rendering-article  
- http://stevekarolewics.com/articles/anti-ghosting-taa.html  
- http://www.dice.se/wp-content/uploads/2014/12/GDC11_DX11inBF3_Public.pdf  
- https://www.elopezr.com/temporal-aa-and-the-quest-for-the-holy-trail/  
- http://www.gdcvault.com/play/1022970/Temporal-Reprojection-Anti-Aliasing-in  
- http://www.geeks3d.com/20110405/fxaa-fast-approximate-anti-aliasing-demo-glsl-opengl-test-radeon-geforce/  
- http://www.geforce.com/whats-new/articles/introducing-the-geforce-gtx-680-gpu#fxaa  
- http://www.iryoku.com/smaa/  
- https://www.rastergrid.com/blog/gpu-tech/2021/10/multisampling-primer/  

### Blending
- https://github.com/dtrebilco/PreMulAlpha  
- https://tylerxhobbs.com/essays/2017/a-generative-approach-to-simulating-watercolor-paints  

### Compression
- http://aras-p.info/texts/CompactNormalStorage.html  
- https://bartwronski.com/2017/04/02/small-float-formats-r11g11b10f-precision/  
- https://shaneycg.github.io/ducktales-remastered-texture-compression/  
- http://www.intrinsic-engine.com/reverse-z-cheat-sheet/  
- http://www.reedbeta.com/blog/understanding-bcn-texture-compression-formats/  
- https://www.yosoygames.com.ar/wp/2018/03/vertex-formats-part-1-compression/  

### Dithering
- https://bartwronski.com/2016/10/30/dithering-in-games-mini-series/  
- https://blog.frost.kiwi/GLSL-noise-and-radial-gradient/  
- https://loopit.dk/banding_in_games.pdf  
- http://www.visualextract.com/posts/color-banding/  

### Dof
- https://blog.voxagon.se/2018/05/04/bokeh-depth-of-field-in-single-pass.html  

### Geometry
- https://dubiousconst282.github.io/2024/10/03/voxel-ray-tracing/  
- https://jglrxavpok.github.io/2024/01/19/recreating-nanite-lod-generation.html  
- https://jglrxavpok.github.io/2024/08/21/recreating-nanite-raytracing.html  
- https://jms55.github.io/posts/2024-06-09-virtual-geometry-bevy-0-14/  
- https://nickmcd.me/2021/04/04/high-performance-voxel-engine/  
- https://people.engr.tamu.edu/schaefer/research/iso_simplicial.pdf  
- https://themaister.net/blog/2024/01/17/modernizing-granites-mesh-rendering/  
- https://www.jakelow.com/blog/hobby-curves  
- https://www.willusher.io/graphics/2024/04/22/webgpu-marching-cubes  

### Gpu
- https://poniesandlight.co.uk/reflect/bitonic_merge_sort/  

#### Sorting
- https://linebender.org/wiki/gpu/sorting/  

### Hdr
- https://bartwronski.com/2016/08/29/localized-tonemapping/  
- http://filmicworlds.com/blog/minimal-color-grading-tools/  
- https://john-chapman.github.io/2017/08/23/dynamic-local-exposure.html  
- https://wolf.nereid.pl/posts/image-viewer/#fnref:26  

### Lens flare
- http://bitsquid.blogspot.com/2017/07/physically-based-lens-flare.html  
- http://john-chapman-graphics.blogspot.com/2013/02/pseudo-lens-flare.html  

### Lighting
- https://aaltodoc.aalto.fi/server/api/core/bitstreams/ab0d594b-da79-4402-88ca-3811b39745e6/content  

#### Brdf
- http://blog.selfshadow.com/publications/s2013-shading-course/rad/s2013_pbs_rad_notes.pdf  
- http://blog.selfshadow.com/publications/s2015-shading-course/rad/s2015_pbs_rad_slides.pdf  
- https://blog.selfshadow.com/publications/s2017-shading-course/imageworks/s2017_pbs_imageworks_slides_v2.pdf  
- https://blog.selfshadow.com/publications/s2020-shading-course/patry/slides/  
- https://blog.tobias-franke.eu/2014/03/30/notes_on_importance_sampling.html  
- https://cseweb.ucsd.edu/%7Etzli/cse272/homework1.pdf  
- https://dassaultsystemes-technology.github.io/EnterprisePBRShadingModel/spec-2021x.md.html  
- http://filmicworlds.com/blog/optimizing-ggx-shaders-with-dotlh/  
- https://google.github.io/filament/Filament.md.html  
- http://graphicrants.blogspot.com/2013/08/specular-brdf-reference.html  
- https://schuttejoe.github.io/post/ggximportancesamplingpart1/  
- https://seblagarde.wordpress.com/2012/01/08/pi-or-not-to-pi-in-game-lighting-equation/  
- http://www.codinglabs.net/article_physically_based_rendering_cook_torrance.aspx  

#### Gi
- https://basesandframes.wordpress.com/2016/05/11/spherical-harmonic-lighting-the-gritty-details/  
- http://copypastepixel.blogspot.com/2017/04/real-time-global-illumination.html?m=1  
- https://extremeistan.wordpress.com/2014/05/11/realtime-global-illumination-techniques-collection/  
- https://grahamhazel.com/blog/2017/12/22/converting-sh-radiance-to-irradiance/  
- https://handmade.network/p/75/monter/blog/p/7421-engine_work__ddgi_light_probe_depth_data_compression#23186  
- https://imdoingitwrong.wordpress.com/2011/04/14/spherical-harmonics-wtf/  
- http://intro-to-restir.cwyman.org/  
- http://madebyevan.com/shaders/lightmap/  
- https://mynameismjp.wordpress.com/2016/10/09/new-blog-series-lightmap-baking-and-spherical-gaussians/  
- https://mynameismjp.wordpress.com/2016/10/09/sg-series-part-6-step-into-the-baking-lab/  
- https://ndotl.wordpress.com/2018/08/29/baking-artifact-free-lightmaps/  
- http://patapom.com/blog/SHPortal/  
- http://simonstechblog.blogspot.com/2013/01/implementing-voxel-cone-tracing.html  
- https://www.sjbrown.co.uk/posts/ambient-and-directional-lighting-in-spherical-harmonics/  
- https://www.slideshare.net/DICEStudio/style-and-gameplay-in-the-mirrors-edge  
- http://xlgames-inc.github.io/posts/sphericalharmonics1/  

#### Ibl
- http://blog.hvidtfeldts.net/index.php/2012/10/image-based-lighting/  
- https://chetanjags.wordpress.com/2015/08/26/image-based-lighting/  
- https://elalish.blogspot.com/2020/11/environment-lighting.html  
- https://interplayoflight.wordpress.com/2013/04/29/parallax-corrected-cubemapping-with-any-cubemap/  
- https://seblagarde.wordpress.com/2012/06/10/amd-cubemapgen-for-physically-based-rendering/  
- https://seblagarde.wordpress.com/2012/09/29/image-based-lighting-approaches-and-parallax-corrected-cubemap/  
- http://www.trentreed.net/blog/physically-based-shading-and-image-based-lighting/  
- http://xlgames-inc.github.io/posts/improvedibl/  

#### Light
- http://blog.magnum.graphics/guest-posts/area-lights-with-ltcs/  
- https://ciechanow.ski/lights-and-shadows/  
- http://www.elopezr.com/rendering-line-lights/  

#### Shading
- http://artisaverb.info/PBT.html  
- http://blog.selfshadow.com/2011/07/22/specular-showdown/  
- https://ivokabel.github.io/2018/05/15/rendering-layered-materials.html  
- http://renderwonk.com/publications/s2010-shading-course/hoffman/s2010_physically_based_shading_hoffman_a_notes.pdf  
- https://seblagarde.files.wordpress.com/2015/07/course_notes_moving_frostbite_to_pbr_v32.pdf  
- https://seblagarde.wordpress.com/tag/physically-based-rendering/  
- http://www.alexandre-pestana.com/physically-based-rendering-viewer/  
- http://www.crytek.com/download/2014_03_25_CRYENGINE_GDC_Schultz.pdf  
- https://www.khronos.org/webgl/wiki_1_15/images/2016-07-28_WebGL_BOF_PBR.pdf  

### Lod
- https://shaderbits.com/blog/octahedral-impostors/  

### Motion blur
- http://john-chapman-graphics.blogspot.com/2013/01/per-object-motion-blur.html  

### Normal mapping
- http://apoorvaj.io/exploring-bump-mapping-with-webgl.html  
- http://blog.selfshadow.com/publications/blending-in-detail/  
- https://casual-effects.com/research/McGuire2005Parallax/index.html  
- https://developer.amd.com/wordpress/media/2012/10/Tatarchuk-ParallaxOcclusionMapping-Sketch-print.pdf  
- https://learnopengl.com/Advanced-Lighting/Parallax-Mapping  
- https://marmosetco.tumblr.com/post/81245981087  
- http://sunandblackcat.com/tipFullView.php?l=eng&topicid=28  

### Path tracing
- https://graphics.pixar.com/library/RendermanTog2018/paper.pdf  

### Pipeline
- https://anki3d.org/gpu-driven-rendering-in-anki-a-high-level-overview/  
- https://blog.traverseresearch.nl/an-update-to-our-render-graph-17ca4154fd23  
- http://diaryofagraphicsprogrammer.blogspot.com/2018/03/triangle-visibility-buffer.html  
- http://filmicworlds.com/blog/visibility-buffer-rendering-with-material-graphs/  
- https://forum.beyond3d.com/threads/modern-textureless-deferred-rendering-techniques.57611/  
- https://github.com/AmanSachan1/WebGL-Clustered-Deferred-Forward-Plus#webgl-clustered-deferred-and-forward-shading  
- https://golden-mandolin-675.notion.site/How-Does-Unreal-Engine-5-2-Render-a-Cube-52dbdfdc78b3426da99908e7ba552b89  
- http://leifnode.com/2015/05/tiled-deferred-shading/  
- https://web.archive.org/web/20240808035830if_/https://hanecci.hatenadiary.org/entry/20130818/p1  
- https://wickedengine.net/2018/01/10/optimizing-tile-based-light-culling/  
- https://www.aortiz.me/2018/12/21/CG.html  
- https://www.elopezr.com/a-macro-view-of-nanite/  

#### Shading
- https://therealmjp.github.io/posts/light-indexed-deferred-rendering/  
- https://www.cse.chalmers.se/~uffe/clustered_shading_preprint.pdf  
- https://www.realtimerendering.com/blog/deferred-lighting-approaches/  

### Point cloud
- https://www.magnopus.com/blog/how-we-render-extremely-large-point-clouds  

### Postprocess
- https://blog.maximeheckel.com/posts/on-crafting-painterly-shaders/  

### Procedural

#### Vegetation
- https://medium.com/@kacper.szwajka842/gpu-run-time-procedural-placement-on-terrain-cc874e39bbfb  

### Rasterization
- http://chrishecker.com/Miscellaneous_Technical_Articles  
- https://fgiesen.wordpress.com/2013/02/10/optimizing-the-basic-rasterizer/  
- https://github.com/ssloy/tinyrenderer/wiki  
- https://media.contentapi.ea.com/content/dam/ea/seed/presentations/seed-coverage-bitmasks-mittring.pdf  
- http://www.cbloom.com/3d/techdocs/pipeline.txt  
- https://www.scratchapixel.com/lessons/3d-basic-rendering/rasterization-practical-implementation/visibility-problem-depth-buffer-depth-interpolation  

### Ray tracing
- http://blog.hvidtfeldts.net/index.php/category/raytracing/  
- https://blog.yiningkarlli.com/2018/10/bidirectional-mipmap.html  
- https://diharaw.github.io/post/adventures_in_hybrid_rendering/  
- https://gist.github.com/h3r2tic/ba39300c2b2ca4d9ca5f6ff22350a037  
- http://hughsk.io/fragment-foundry/chapters/01-hello-world.html  
- http://jamie-wong.com/2016/07/15/ray-marching-signed-distance-functions/  
- https://reindernijhoff.net/2019/03/wolfenstein-raytracing-on-using-webgl1/  
- https://www.osar.fr/notes/logspherical/  
- https://www.tylermw.com/throwing-shade/  

### Raymarching
- https://jarllarsson.github.io/gen/gunkraymarcher.html  

### Sampling
- https://bartwronski.com/2021/02/15/bilinear-down-upsampling-pixel-grids-and-that-half-pixel-offset/  
- https://bartwronski.com/2020/04/14/bilinear-texture-filtering-artifacts-alternatives-and-frequency-domain-analysis/  
- https://bassser.tumblr.com/post/11626074256/reconstructing-position-from-depth-buffer  
- https://blog.demofox.org/2016/02/22/gpu-texture-sampler-bezier-curve-evaluation/  
- https://blog.demofox.org/2019/06/25/generating-blue-noise-textures-with-void-and-cluster/  
- https://blog.demofox.org/2017/05/29/when-random-numbers-are-too-random-low-discrepancy-sequences/  
- http://c0de517e.blogspot.com/2016/02/downsampled-effects-with-depth-aware.html  
- https://eleni.mutantstargoat.com/hikiko/depth-aware-upsampling-3-1/  
- https://extremelearning.com.au/how-to-generate-uniformly-random-points-on-n-spheres-and-n-balls/  
- https://extremelearning.com.au/unreasonable-effectiveness-of-quasirandom-sequences/  
- http://graphicrants.blogspot.com/2013/12/tone-mapping.html  
- http://holger.dammertz.org/stuff/notes_HammersleyOnHemisphere.html  
- https://indieburg.com/blog/posts/20200110-mip-map-folding  
- https://interplayoflight.wordpress.com/2023/12/17/a-gentler-introduction-to-restir/  
- https://lisyarus.github.io/blog/posts/multiple-importance-sampling.html  
- http://lousodrome.net/blog/light/2017/01/03/intersection-of-a-ray-and-a-cone/  
- https://merlin3d.wordpress.com/2018/10/04/correlated-multi-jittered-sampling-on-gpu/  
- http://rastergrid.com/blog/2010/09/efficient-gaussian-blur-with-linear-sampling/  
- https://surma.dev/things/ditherpunk/  
- https://thomasdeliot.wixsite.com/blog/single-post/2020/03/30/Biquadratic-interpolation-with-independent-sample-weights  
- https://vec3.ca/bicubic-filtering-in-fewer-taps/  
- https://www.gamedevs.org/uploads/fast-extraction-viewing-frustum-planes-from-world-view-projection-matrix.pdf  
- https://www.intel.com/content/dam/develop/external/us/en/documents/fast-fourier-transform-for-image-processing-in-directx-11-541444.pdf  
- http://www.johncostella.com/magic/  
- https://www.reedbeta.com/blog/hash-functions-for-gpu-rendering/  

### Screenspace

#### Ao
- https://frictionalgames.blogspot.com/2014/01/tech-feature-ssao-and-temporal-blur.html  
- http://john-chapman-graphics.blogspot.com/2013/01/ssao-tutorial.html  
- https://ktstephano.github.io/rendering/stratusgfx/svsm  
- https://mtnphil.wordpress.com/2013/06/26/know-your-ssao-artifacts/  
- https://panoskarabelas.com/posts/screen_space_shadows/  
- http://www.derschmale.com/2013/12/20/an-alternative-implementation-for-hbao-2/  

#### Reflection
- https://andrew-pham.blog/2019/07/31/screen-space-reflections/  
- https://bartwronski.com/2014/03/23/gdc-follow-up-screenspace-reflections-filtering-and-up-sampling/  
- http://hacksoflife.blogspot.com/2020/10/a-tip-for-hiz-ssr-parametric-t-tracing.html  
- https://joostdevblog.blogspot.com/2020/10/screen-space-reflections-in-blightbound.html  
- https://lukas-hermanns.info/download/bachelorthesis_ssct_lhermanns.pdf  
- http://remi-genin.fr/blog/screen-space-plane-indexed-reflection-in-ghost-recon-wildlands/  
- http://roar11.com/2015/07/screen-space-glossy-reflections/  
- https://sakibsaikia.github.io/graphics/2016/12/26/Screen-Space-Reflection-in-Killing-Floor-2.html  
- https://sites.google.com/site/monshonosuana/directxの話/directxの話-第149回?authuser=0  
- https://sugulee.wordpress.com/2021/01/19/screen-space-reflections-implementation-and-optimization-part-2-hi-z-tracing-method/  
- https://www.jpgrenier.org/ssr.html  

#### Ssr
- https://zznewclear13.github.io/posts/screen-space-reflection-en/  

### Sdf
- https://blog.demofox.org/2016/02/29/fast-voronoi-diagrams-and-distance-dield-textures-on-the-gpu-with-the-jump-flooding-algorithm/  
- https://iquilezles.org/articles/  
- http://litherum.blogspot.com/2015/02/end-to-end-tour-of-text-rendering.html?m=1  
- https://redpenguin101.github.io/html/posts/2025_01_21_voronoi.html  

### Shader

#### 2d
- https://bgolus.medium.com/the-best-darn-grid-shader-yet-727f9278b9d8  

### Shadow
- http://developer.download.nvidia.com/SDK/10.5/opengl/src/cascaded_shadow_maps/doc/cascaded_shadow_maps.pdf  
- https://developer.nvidia.com/gpugems/gpugems/part-ii-lighting-and-shadows/chapter-14-perspective-shadow-maps-care-and-feeding  
- https://efficientshading.com/wp-content/uploads/s2015_shadows.pdf  
- https://forums.tigsource.com/index.php?topic=8803.0  
- https://lukaskalbertodt.github.io/2023/11/18/tiled-soft-shadow-volumes.html  
- https://worldoffries.wordpress.com/2019/03/26/what-good-is-hundreds-of-lights-with-out-hundreds-of-shadows/  
- https://www.bendstudio.com/blog/inside-bend-screen-space-shadows/  
- http://www.codinglabs.net/tutorial_opengl_deferred_rendering_shadow_mapping.aspx  
- https://www.gamedev.net/tutorials/programming/graphics/contact-hardening-soft-shadows-made-fast-r4906/  
- http://www.opengl-tutorial.org/intermediate-tutorials/tutorial-16-shadow-mapping/  

### Snow
- https://www.gdcvault.com/play/1020177/Deformable-Snow-Rendering-in-Batman  

### Stereogram
- https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch41.html  

### Swapchain
- https://erfan-ahmadi.github.io/blog/Nabla/fif  
- https://marcelbraghetto.github.io/a-simple-triangle/2019/07/27/part-24/  
- https://martinfullerblog.wordpress.com/2023/10/11/dynamic-resolution-scaling-drs-implementation-best-practice/  
- https://medium.com/@tglaiel/how-to-make-your-game-run-at-60fps-24c61210fe75  

#### Vsync
- https://raphlinus.github.io/ui/graphics/gpu/2021/10/22/swapchain-frame-pacing.html  
- https://www.intel.com/content/www/us/en/developer/articles/code-sample/sample-application-for-direct3d-12-flip-model-swap-chains.html  

### Vfx
- https://housemarque.com/news/2021/9/15/returnal-vfx-breakdown  

### Visibility
- https://bazhenovc.github.io/blog/post/gpu-driven-occlusion-culling-slides-lif/  
- https://fgiesen.wordpress.com/2010/10/17/view-frustum-culling/  
- https://interplayoflight.wordpress.com/2017/11/15/experiments-in-gpu-based-occlusion-culling/  
- https://zeuxcg.org/2009/01/31/view-frustum-culling-optimization-introduction/  
- https://zeuxcg.org/2009/01/31/view-frustum-culling-optimization-introduction/  

### Volumetric
- https://arxiv.org/abs/1612.04336  
- https://chuckleplant.github.io/2017/05/28/light-shafts.html  
- https://ebruneton.github.io/precomputed_atmospheric_scattering/  
- https://github.com/ebruneton/clear-sky-models  
- https://slsdo.github.io/volumetric-cloud/  
- http://www.eugenedeon.com/wp-content/uploads/2021/11/hitchhiker_v0.3_graphics.pdf  
- https://www.guerrilla-games.com/read/the-real-time-volumetric-cloudscapes-of-horizon-zero-dawn  
- http://www.thetenthplanet.de/archives/4519  

### Water
- https://auzaiffe.wordpress.com/2024/08/08/mapping-ffts-to-a-sphere-an-unexpected-journey/  
- https://gikster.dev/posts/Ocean-Simulation/  
- https://medium.com/@evanwallace/rendering-realtime-caustics-in-webgl-2a99a29a0b2c  
- https://seblagarde.wordpress.com/2012/12/10/observe-rainy-world/  
- https://web.archive.org/web/20111113000538/http://www.gamasutra.com/gdce/2001/jensen/jensen_04.htm  
- https://web.archive.org/web/20180315084809/https://community.eidosmontreal.com/blogs/hitman-ocean-tech  
- https://www.fxguide.com/featured/assassins-creed-iii-the-tech-behind-or-beneath-the-action/  
- https://www.gamedeveloper.com/programming/mud-and-water-of-spintires-mudrunner#:~:text=THE%20WATER%20OF%20MUDRUNNER

## Gpu
- http://betteros.org/tut/graphics1.php  
- https://cachemiss.xyz/blog/parallel-reduce-and-scan-on-the-GPU  
- https://devblogs.nvidia.com/the-peak-performance-analysis-method-for-optimizing-any-gpu-workload/  
- https://developer.samsung.com/game/gpu-framebuffer  
- https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/  
- http://fragmentbuffer.com/gpu-performance-for-game-artists/  
- https://gankra.github.io/blah/text-hates-you/  
- https://giordi91.github.io/post/vegaisa/  
- https://github.com/MattPD/cpplinks/blob/master/comparch.gpu.md  
- https://github.com/dolphin-emu/dolphin/blob/master/Source/Core/VideoCommon/DriverDetails.h  
- https://interplayoflight.wordpress.com/2021/04/18/how-to-read-shader-assembly/  
- http://latchup.blogspot.com/2016/02/life-of-triangle.html  
- http://litherum.blogspot.com/2023/10/implementing-gpus-programming-model-on.html  
- https://pixeljetstream.blogspot.com/2015/02/life-of-triangle-nvidias-logical.html  
- https://raphlinus.github.io/rust/graphics/gpu/2019/05/08/modern-2d.html  
- https://seblagarde.wordpress.com/2014/12/01/inverse-trigonometric-functions-gpu-optimization-for-amd-gcn-architecture/  
- http://www.humus.name/Articles/Persson_LowLevelThinking.pdf  
- http://www.humus.name/Articles/Persson_LowlevelShaderOptimization.pdf  

### Debug
- https://vksegfault.github.io/posts/gentle-intro-gpu-inner-workings/  

### Dx12
- https://alextardif.com/DX12Tutorial.html  
- https://digitalerr0r.net/2015/08/19/quickstart-directx-12-programming/  
- http://diligentgraphics.com/diligent-engine/architecture/d3d12/  
- https://docs.microsoft.com/en-us/windows/win32/direct3d12/directx-12-programming-guide  
- https://www.3dgep.com/learning-directx-12-1/  

### Hardware
- https://86box.net/2025/02/25/riva128-part-1.html#fnref:mipmap  

### Maths
- https://theorangeduck.com/page/closed-form-matrix-decompositions  

### Performance
- https://gpu-primitives-course.github.io/  

### Pipeline
- https://timur.hu/blog/2022/mesh-and-task-shaders  

### Security
- https://chromium.googlesource.com/chromium/src/+/main/docs/security/research/graphics/webgpu_technical_report.md  

### Shader

#### Compiler
- https://devlog.hexops.com/2024/building-the-directx-shader-compiler-better-than-microsoft/  

### Thread
- https://logins.github.io/programming/2020/12/31/RenderThreadJobification.html  

### Vulkan
- https://alain.xyz/blog/raw-vulkan#overview  
- http://anki3d.org/porting-anki-to-vulkan/  
- https://blog.nap-labs.tech/d0/dfd/md_articles_001_nap_opengl_to_vulkan  
- https://github.com/David-DiGioia/vulkan-diagrams  
- https://github.com/diharaw/hybrid-rendering  
- http://themaister.net/blog/2019/04/20/a-tour-of-granites-vulkan-backend-part-3/  
- https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf  
- https://zeux.io/2019/07/17/serializing-pipeline-cache/  
- https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/  

### Webgpu
- https://floooh.github.io/2023/10/16/sokol-webgpu.html  

## Prog
- https://anotherproducer.com/online-tools-for-musicians/midi-cc-list/  
- http://breno.sarmen.to/midi_documentation/list.html  
- http://cocoamine.net/blog/2015/03/20/replacing-photoshop-with-nsstring/  
- http://eastfarthing.com/blog/2020-09-14-decoder/  
- https://github.com/cameronswinoga/yabfc/wiki/Generating-executable-files-from-scratch  
- https://github.com/nothings/single_file_libs  
- https://github.com/nothings/stb  
- https://github.com/syoyo/tinyexr  
- https://graphitemaster.github.io/fibers/  
- http://hamelot.io/visualization/using-ffmpeg-to-convert-a-set-of-images-into-a-video/  
- https://jackschaedler.github.io/handwriting-recognition/  
- http://littleosbook.github.io/#introduction  
- https://medium.com/retronator-magazine/pixels-and-voxels-the-long-answer-5889ecc18190  
- http://mikeos.sourceforge.net/write-your-own-os.html  
- https://nickfever.com/Music/midi-cc-list  
- https://raphlinus.github.io/curves/2021/03/11/bezier-fitting.html  
- https://redsweater.com/blog/2083/the-power-of-plist  
- http://si.org/projects/project1/index.html  
- https://sonnati.wordpress.com/2014/06/20/h265-part-i-technical-overview/  
- http://tfpsly.free.fr/bookmarks.html  
- http://utf8everywhere.org/  
- https://viewsourcecode.org/snaptoken/kilo/index.html  
- http://web.eecs.umich.edu/~sugih/courses/eecs487/glfw-howto/  
- https://zetcode.com/gui/winapi/  

### Arm
- https://blog.yiningkarlli.com/2021/05/porting-takua-to-arm-pt1.html  

### Assembly
- https://mariokartwii.com/armv8/  

### Build
- https://eli.thegreenplace.net/2013/07/09/library-order-in-static-linking  
- https://mcyoung.xyz/2021/06/01/linker-script/  

### Demoscene
- https://6octaves.blogspot.com/2017/06/interview-with-japanese-demoscener.html?m=1  
- https://alia-traces.github.io/demoscene/metal/pathtracing/2020/07/24/reconstruction.html  
- https://docs.google.com/presentation/d/1RWzos-3yguFRVSveNPu4vN7b5BQWjcKEjcdrB5u2okE/mobilepresent?slide=id.g3de4468ac9_0_661  
- https://gargaj.tumblr.com/post/178117551485/along-for-the-ride-a-reasonably-complex-demo  
- https://github.com/runestubbe/Crinkler  
- https://in4k.github.io/  
- https://medium.com/@jerry.ylilammi/making-of-newton-protocol-e9ccde41af30  
- http://www.amietia.com/oscarschair.html  
- http://www.lofibucket.com/articles/64k_intro.html  

### Font
- https://gwern.net/sidenote  

### Fun
- https://eieio.games/nonsense/game-11-flappy-bird-finder/#fnref:4  
- https://www.dangermouse.net/esoteric/piet.html  

### Hardware
- https://ctf.re/windows/kernel/pcie/tutorial/2023/02/14/pcie-part-1/  

### Kinect
- http://blog.nelga.com/setup-microsoft-kinect-on-mac-os-x-10-9-mavericks/  
- https://github.com/benMcChesney/OF_Kinect_Tutorials  

### Memory
- https://faultlore.com/blah/deinitialize-me-maybe/  
- https://muxup.com/2023q4/storing-data-in-pointers  
- https://www.gingerbill.org/series/memory-allocation-strategies/  

### Multithread
- https://agraphicsguynotes.com/posts/fiber_in_cpp_understanding_the_basics/  
- https://poniesandlight.co.uk/reflect/coroutines_job_system/  

### Reverse engineering
- https://migeel.sk/blog/2023/09/15/reverse-engineering-natively-compiled-dotnet-apps/  

### Security
- https://axleos.com/exploiting-the-iphone-4-part-1-gaining-entry/  
- https://blog.isosceles.com/the-webp-0day/  
- https://www.reversemode.com/2023/10/reversing-france-identite-new-french.html  

### Tutorial
- http://antongerdelan.net/opengl/index.html  
- https://catlikecoding.com/unity/tutorials/  
- https://cs184.eecs.berkeley.edu/sp23  
- http://gameprogrammingpatterns.com/contents.html  
- https://learnopengl.com  
- https://pomax.github.io/bezierinfo/  
- https://thebookofshaders.com  
- http://www.cs.uu.nl/docs/vakken/magr/portfolio/  
- http://www.essentialmath.com/tutorial.htm  
- http://www.lighthouse3d.com  
- http://www.opengl-tutorial.org  
- https://www.roxlu.com  
- https://www.scratchapixel.com  

## Retro
- http://codetapper.com/amiga/sprite-tricks/  
- https://fms-cat.github.io/thump/  
- https://mitxela.com/projects/console  
- http://skilldrick.github.io/easy6502/#snake  

### Dreamcast
- http://cadcdev.sourceforge.net/softprj/kos/setup.php  
- https://dcemulation.org/?title=Development  
- https://dcemulation.org/phpBB/viewtopic.php?f=29&t=51558  
- https://dcemulation.org/phpBB/viewtopic.php?f=29&t=99166  
- http://dmitry.gr/index.php?r=05.Projects&proj=25.%20VMU%20Hacking  

### Glide
- https://glide.sourceforge.net  
- http://www.gamers.org/dEngine/xf3D/glide/glidepgm.htm  

### Nintendo
- https://38leinad.wordpress.com/2012/03/03/gameboy-development-on-mac-os-x/  
- https://cturt.github.io/cinoop.html  
- http://gbdev.gg8.se/wiki/articles/Tutorials  
- https://github.com/dekuNukem/Nintendo_Switch_Reverse_Engineering  
- https://github.com/devkitPro/libnds  
- http://kylehalladay.com/gba.html  
- http://libnds.devkitpro.org/videoGL_8h.html  
- https://media.ccc.de/v/33c3-8029-the_ultimate_game_boy_talk  
- http://members.iinet.net.au/~freeaxs/gbacomp/  
- http://n64.icequake.net/doc/n64intro/kantan/step2/index1.html  
- http://problemkaputt.de/gbatek.htm  
- https://web.archive.org/web/20110415235959/http://home.no:80/neogeo/HOVEDSIDE_INDEX/GBA_HOVEDSIDE_INDEX_ENGELSK/index.html  
- http://www.coranac.com/tonc/text/toc.htm  
- https://www.cs.rit.edu/~tjh8300/CowBite/CowBiteSpec.htm  

### Sony
- http://archive.arstechnica.com/reviews/1q00/playstation2/m-ee-1.html  
- https://arstechnica.com/features/2000/04/ps2vspc/  
- https://basesandframes.wordpress.com/2016/07/25/procedural-rendering-on-ps2/  
- https://bitbucket.org/glampert/ps2dev-tests/src/cb6f77908e2fe4f775bfaceba66ba14d93a244c2/source/framework/?at=master  
- https://cturt.github.io/freedvdboot.html  
- https://cturt.github.io/ps4.html  
- https://en.wikipedia.org/wiki/PlayStation_2_technical_specifications  
- https://github.com/ps2dev  
- http://glampert.com/2015/02-27/ps2-homebrew-setting-up-the-environment/  
- http://lukasz.dk/playstation-2-programming/an-introduction-to-ps2dev/  
- http://lukasz.dk/playstation-2-programming/archive/  
- http://ps2linux.no-ip.info/playstation2-linux.com/projects/3dprotut/index.html  
- http://web.archive.org/web/20150725052552/http://www.hsfortuna.pwp.blueyonder.co.uk/  

### Techno
- https://jcs.org/2025/02/26/imacg4k  

### Vectrex
- https://vandenbran.de/post/2016-02-01-a-modern-toolchain-for-vectrex-development/  
- http://www.gametronik.com/site/emulation/vectrex/  
- https://www.playvectrex.com/designit/chrissalo/toc.htm  

### Video
- http://blog.tynemouthsoftware.co.uk/2023/10/how-the-zx81-generates-video.html  
- https://pcbjunkie.net/index.php/guides/generating-video-with-a-microcontroller/  
- https://www.backoldgaming.com/topic/read/lart-de-la-sync  
- https://www.bigmessowires.com/2023/10/04/classic-macintosh-video-signals-demystified-designing-a-mac-to-vga-adapter-with-lm1881/  

# Graphics programming virtual meetup list <a id="gpvm"></a>
https://github.com/Graphics-Programming-Virtual-Meetup/resources?tab=readme-ov-file

## Table of contents
  - [Beginner friendly](#beginner-friendly)
  - [Meta-links](#meta-links)
  - [Overview](#overview)
    - [Books](#books)
    - [Courses](#courses)
  - [Advice](#advice)
  - [Math](#math)
    - [Tutorials](#tutorials)
    - [Books](#books-1)
    - [Homogeneous Coordinate](#homogeneous-coordinate)
    - [Rotation](#rotation)
    - [Quaternions](#quaternions)
    - [Linear Algebra / Matrices](#linear-algebra--matrices)
    - [Barycentric Coordinates](#barycentric-coordinates)
    - [Geometric Algebra](#geometric-algebra)
    - [Curves and Surfaces](#curves-and-surfaces)
    - [Implementing Math Library](#implementing-math-library)
    - [Circular/Spherical harmonics](#circularspherical-harmonics)
    - [Geometry](#geometry)
  - [Ray Tracing](#ray-tracing)
    - [Intro to Ray Tracing](#intro-to-ray-tracing)
    - [Ray Tracing Books](#ray-tracing-books)
    - [Ray Tracing Courses](#ray-tracing-courses)
    - [Algorithms](#algorithms)
    - [BVH](#bvh)
    - [Sampling & Variance Reduction](#sampling--variance-reduction)
    - [Intersection](#intersection)
    - [Denoising](#denoising)
    - [GPU Ray Tracing](#gpu-ray-tracing)
  - [Rasterization](#rasterization)
    - [Graphics Pipeline](#graphics-pipeline)
    - [Shading Techniques](#shading-techniques)
    - [Culling](#culling)
    - [Depth Buffer](#depth-buffer)
    - [Software Rasterization](#software-rasterization)
  - [Graphics Effects](#graphics-effects)
    - [Normal Mapping](#normal-mapping)
    - [Hash Functions](#hash-functions)
    - [Dithering](#dithering)
    - [Shadow](#shadow)
    - [Ambient Occlusion](#ambient-occlusion)
    - [Reflection](#reflection)
    - [Transparency](#transparency)
    - [Ray Marching and SDF](#ray-marching-and-sdf)
    - [Line, Edge, and Outline Drawing](#line-edge-and-outline-drawing)
    - [Text Rendering](#text-rendering)
    - [Tessellation](#tessellation)
    - [Voxel Rendering](#voxel-rendering)
    - [Volume Rendering](#volume-rendering)
    - [Dithering](#dithering-1)
    - [Sprite Rendering](#sprite-rendering)
    - [Atmosphere Scattering](#atmosphere-scattering)
    - [Grass Rendering](#grass-rendering)
  - [PBR](#pbr)
  - [Textures](#textures)
    - [Mipmapping](#mipmapping)
    - [Texture Compression](#texture-compression)
    - [Texture Bombing](#texture-bombing)
  - [Shader Programming](#shader-programming)
  - [Compute](#compute)
    - [Introduction to compute shader](#introduction-to-compute-shader)
    - [GPU Architecture](#gpu-architecture)
    - [Parallel Algorithms](#parallel-algorithms)
    - [Atomics](#atomics)
  - [Color, HDR, and Tone Mapping](#color-hdr-and-tone-mapping)
  - [Sampling and anti-aliasing](#sampling-and-anti-aliasing)
  - [Animation](#animation)
  - [Geometry](#geometry-1)
    - [Geometry representations](#geometry-representations)
    - [Iso-surface methods](#iso-surface-methods)
    - [Libraries](#libraries)
  - [Physics and Simulation](#physics-and-simulation)
    - [Physics-Based Animation](#physics-based-animation)
    - [Attractors](#attractors)
    - [Optics](#optics)
  - [APIs](#apis)
    - [Ray Tracing API](#ray-tracing-api)
    - [OpenGL](#opengl)
    - [Vulkan](#vulkan)
    - [DirectX 12](#directx-12)
    - [WebGL](#webgl)
    - [WebGPU](#webgpu)
  - [System Design](#system-design)
    - [Renderer Architecture](#renderer-architecture)
    - [GPU-driven rendering](#gpu-driven-rendering)
  - [Scene Description](#scene-description)
  - [General Programming](#general-programming)
    - [Meta-links](#meta-links-1)
    - [Engine Development](#engine-development)
    - [Performance Optimization](#performance-optimization)
    - [High-level Programming](#high-level-programming)
    - [Game loop](#game-loop)
    - [Floating-point numbers](#floating-point-numbers)
    - [Memory Allocation & Management](#memory-allocation--management)
  - [Tools/libraries](#toolslibraries)
    - [Debuggers](#debuggers)
    - [Profilers](#profilers)
    - [Denoiser](#denoiser)
  - [Assets](#assets)
    - [Polygonal Model & Scene](#polygonal-model--scene)
    - [Materials](#materials)
    - [Voxel Data](#voxel-data)

## Beginner friendly

Here is a list of resources suitable for beginners,
though intermediate or advanced folks can also benefit from them.

- [Learn OpenGL](https://learnopengl.com/) - Learn OpenGL is the definitive resource for learning real-time renderer techniques as beginners. Even though it is an OpenGL tutorial, it also teaches rendering techniques at the same time.
- [Ray Tracing in One Weekend series](https://raytracing.github.io/) - Those three short books explain basic concepts of path tracing and implement a software renderer from scratch.
- 🎥 [CMU's introductory to Computer Graphics course](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E) -
A comprehensive introduction to various topics in computer graphics.
- [Catlike Coding](https://catlikecoding.com/) - Focuses on C# and shaders in Unity.
- [Book Of Shaders](https://thebookofshaders.com/) - The author introduces shaders from an artistic perspective, and the book covers many topics that more engineering-focused resources such as "Learn OpenGL" won't cover.
- [ShaderToy](https://www.shadertoy.com/) - Huge collection of open source techniques to refer to, ranging from very basic to more advanced topics. 

## Meta-links
Resources that curate other resources. Some meta links are omitted here if they are mentioned in other categories.

- [GPU Optimization for GameDev](https://gist.github.com/silvesthu/505cf0cbf284bb4b971f6834b8fec93d)
- [Volumetric Clouds Resources List](https://gist.github.com/pixelsnafu/e3904c49cbd8ff52cb53d95ceda3980e)
- [graphics resources](https://github.com/mattdesl/graphics-resources)
- [Awesome Computer Graphics (luisnts)](https://github.com/luisnts/awesome-computer-graphics)
- [Awesome Computer Graphics (waitin2010)](https://github.com/waitin2010/awesome-computer-graphics)
- [Fun with Computer Graphics](https://github.com/zheng95z/fun-with-computer-graphics)
- [Awesome Graphics Libraries - engines & frameworks](https://github.com/jslee02/awesome-graphics-libraries)
- [Awesome Computer Vision](https://github.com/jbhuang0604/awesome-computer-vision)
- [Awesome Gamedev](https://github.com/ellisonleao/magictools) - Lots of graphics-related stuff.
- [Physics-Based Animation](http://www.physicsbasedanimation.com/) - Contains learning resources and papers.
- [Digital Morphogenesis Resources - Info About Some Different Simulation Techniques](https://github.com/jasonwebb/morphogenesis-resources)
- [Graphics Programming Weekly - Article Database](https://www.jendrikillner.com/article_database/)
- [Graphics Studies Compilation - Adrian Courrèges](https://www.adriancourreges.com/blog/2020/12/29/graphics-studies-compilation/) - Handy compilation of frame breakdown articles
- [Readings on Physically Based Rendering](https://interplayoflight.wordpress.com/2013/12/30/readings-on-physically-based-rendering/) - A collection of resources related to PBR rendering
- [Computer Graphics Resources Materials for Self Study](https://legends2k.github.io/note/cg_resources/)
- [Resources for Beginning Graphics Programming](https://medium.com/vrtigo/resources-for-beginning-graphics-programming-c0da724381bc)

## Overview
### Books
- [Graphics Codex](https://graphicscodex.com/app/app.html) - Free book that contains chapters on physically-based shading and rendering, coding projects, and reference pages.
- [Real-Time Rendering, Fourth Edition](https://www.amazon.com/Real-Time-Rendering-Fourth-Tomas-Akenine-M%C3%B6ller/dp/1138627003)
- [Fundamentals of Computer Graphics 5th Edition](https://www.amazon.com/Fundamentals-Computer-Graphics-Steve-Marschner/dp/0367505037)

### Courses
- [CMU's introductory to Computer Graphics course](https://www.youtube.com/playlist?list=PL9_jI1bdZmz2emSh0UQ5iOdT2xRHFHL7E)
- [6.837: Introduction to Computer Graphics (fall 2020)](https://youtube.com/playlist?list=PLQ3UicqQtfNuBjzJ-KEWmG1yjiRMXYKhh)
- [Introduction to Computer Graphics - Cem Yuksel](https://youtube.com/playlist?list=PLplnkTzzqsZTfYh4UbhLGpI5kGd5oW_Hh)

## Advice
- [Finding Your Home in Game Graphics Programming](http://alextardif.com/LearningGraphics.html) - Presents a high-level overview of the rendering world and resources for getting started in the different specializations
- [Insider guide to tech interviews](https://bartwronski.com/2022/01/04/insider-guide-to-tech-interviews/) - An in-depth analysis of the interview process for experienced developers
- [Graphics Programming – Where To Start?](https://www.stefanpijnacker.nl/article/graphics-programming-where-to-start/) - Advices and resource recommendation for beginning learner

## Math

### Tutorials
- 🎥 [Math For Game Devs](https://www.youtube.com/playlist?list=PLImQaTpSAdsD88wprTConznD1OY1EfK_V) - Video Series from Freya Holmér

### Books
- [immersive linear algebra](http://immersivemath.com/ila/index.html) - Free online book with interactive figures.
- [Mathematics for Computer Graphics](https://www.amazon.com/Mathematics-Computer-Graphics-Undergraduate-Science/dp/1447173341)
- [Mathematics for 3D Game Programming and Computer Graphics, 3rd Edition](https://www.amazon.com/Mathematics-Programming-Computer-Graphics-Third/dp/1435458869)
- [Foundations of Game Engine Development, Volume 1: Mathematics](https://www.amazon.com/Foundations-Game-Engine-Development-Mathematics/dp/0985811749) - Introduces math routines with implementations. It also touches Grassman algebra.

### Homogeneous Coordinate
- [A trip down the graphics pipeline: the homogeneous perspective transform](https://www.ece.uvic.ca/~bctill/20004/additional/homcoord/00210494.pdf)

### Rotation
- [Gimbal lock confusion - Computer Graphics Stack Exchange](https://computergraphics.stackexchange.com/questions/12273/gimbal-lock-confusion)

### Quaternions
- [Visualizing quaternions](https://eater.net/quaternions) - A great intereactive introduction/refresher for quaternions. It focuses on intuition rather than mathematical definitions.

### Linear Algebra / Matrices
- [GPUOpen Matrix Compendium](https://gpuopen.com/learn/matrix-compendium/matrix-compendium-intro/)
- [3Blue1Brown Youtube Channel](https://www.youtube.com/c/3blue1brown) - general math topics, good for linear algebra and calculus.

### Barycentric Coordinates
- [Barycentric Coordinates](https://observablehq.com/@infowantstobeseen/barycentric-coordinates) - An interactive introduction to Barycentric Coordinates

### Geometric Algebra
- [Let's remove Quaternions from every 3D Engine](https://marctenbosch.com/quaternions/) - Introduces *Rotors* in Geometric Algebra.

### Curves and Surfaces
- 🎥 [The Beauty of Bézier Curves](https://www.youtube.com/watch?v=aVwxzDHniEw)
- [Bézier Curves](https://blog.richardekwonye.com/bezier-curves) - An interactive explanation and exploration of Bezier curves

### Implementing Math Library
- [On Vector Math Libraries](https://www.reedbeta.com/blog/on-vector-math-libraries/)
- [GDC18 - Linear Algebra Upgraded](http://www.terathon.com/gdc18_lengyel.pdf) - Designs an affine space type library with distinct vector and point types, and also uses template and union hacks to implement vector swizzling in C++.
- 🎥 [CppCon 2018: Valentin Galea “Rapid Prototyping of Graphics Shaders in Modern C++”](https://www.youtube.com/watch?v=8FoAxasNssA) - Also implemented swizzling with similar techniques.

### Circular/Spherical harmonics
- [Circular Harmonics: Digging in circles](https://valdes.cc/articles/ch.html)
- [Spherical Harmonics for Beginners](https://dickyjim.wordpress.com/2013/09/04/spherical-harmonics-for-beginners/) - Cover the fundamentals of using Spherical Harmonics without delving into the math deeply
- [Spherical Harmonics in Graphics: A Brief Overview](https://gen-graphics.blogspot.com/2017/11/spherical-harmonics-in-graphics-brief.html)
- [Spherical Harmonics - Insights And Fundamentals](https://github.com/AlexSabourinDev/cranberry_blog/blob/master/SphericalHarmonics_Fundamentals.md)
- [Spherical Harmonic Lighting](https://simonstechblog.blogspot.com/2011/12/spherical-harmonic-lighting.html)
- [Stupid Spherical Harmonics (SH) Tricks](https://www.ppsloan.org/publications/StupidSH36.pdf)

### Geometry
- [Visualizing Delaunay Triangulation](https://ianthehenry.com/posts/delaunay/)
- [Point-Based Graphics Metalink](https://www.realtimerendering.com/kesen/PointBasedPaper.html)

## Ray Tracing
### Intro to Ray Tracing
- [Ray Tracing in One Weekend series](https://raytracing.github.io/)
- [An Improved Illumination Model for Shaded Display](https://www.cs.drexel.edu/~david/Classes/Papers/p343-whitted.pdf) - Turner Whitted's original Ray Tracing paper.
- 🎥 [Lecture 18: Monte Carlo Rendering (CMU 15-462/662)](https://youtu.be/FUZJNlRqrAc) - Including a very good introduction to importance sampling.
- [Global Illumination Compendium](https://www.ii.uni.wroc.pl/~anl/cgfiles/TotalCompendium.pdf) - overview of ray tracing/path tracing techniques.
- [Creating a physically-based path tracer](https://alexanderameye.github.io/notes/path-tracer/)

### Ray Tracing Books
- [Physically Based Rendering: From Theory To Implementation Third Edition](https://www.pbr-book.org/) - The definitive book for offline rendering.
- [Ray Tracing Gems](https://www.realtimerendering.com/raytracinggems/rtg/index.html) - Like other "gems" books, it contains standalone chapters on various ray tracing topics.
- [Ray Tracing Gems II](https://www.realtimerendering.com/raytracinggems/rtg2/index.html)
- [Advanced Global Illumination](https://www.amazon.com/Advanced-Global-Illumination-Philip-Dutre/dp/1568813074) - An advanced book that focuses on light transport theory.

### Ray Tracing Courses
- [Dartmouth Rendering Algorithms (Fall21)](https://cs87-dartmouth.github.io/Fall2021/) - The course nicely fills the gap between a Ray Tracing in One Weekend style toy renderer to a more general and fully-fledged renderer that PBRT describes.

### Algorithms
- [Bidirectional Estimators for Light Transport](https://www.cs.jhu.edu/~misha/ReadingSeminar/Papers/Veach94.pdf) - Introduces *bidirectional path tracing*.
- [Monte Carlo Methods for Light Transport Simulation](https://graphics.stanford.edu/papers/veach_thesis/) - the Academy Award-winning Ph.D. thesis by Eric Veach. It starts from *bidirectional light transport algorithms* and introduces *multiple importance sampling* and *Metropolis light transport*

### BVH
- [A Survey on Bounding Volume Hierarchies for Ray Tracing](https://meistdan.github.io/publications/bvh_star/paper.pdf) - Excellent overview paper on BVH.
- [bvh - A modern C++ BVH construction and traversal library](https://github.com/madmann91/bvh) - Implements various algorithms for BVH traversal and construction.

### Sampling & Variance Reduction
- 🎥 [Lecture 19: Variance Reduction (CMU 15-462/662)](https://youtu.be/IQhLk_XaFc8)
- [Flavors of Sampling in Ray Tracing](http://psgraphics.blogspot.com/2018/10/flavors-of-sampling-in-ray-tracing.html)
- [Stratified Sampling of Spherical Triangles](http://www.graphics.cornell.edu/pubs/1995/Arv95c.pdf)
- [Distributing Monte Carlo Errors as a Blue Noise in Screen Space by Permuting Pixel Seeds Between Frames](https://hal.archives-ouvertes.fr/hal-02158423/file/blueNoiseTemporal2019_slides.pdf)
- [A Low-Discrepancy Sampler that Distributes Monte Carlo Errors as a Blue Noise in Screen Space](https://belcour.github.io/blog/slides/2019-sampling-bluenoise/index.html)
- [Rendering in Real Time with Spatiotemporal Blue Noise Textures](https://developer.nvidia.com/blog/rendering-in-real-time-with-spatiotemporal-blue-noise-textures-part-1/) series
- [What is direct lighting (next event estimation) in a ray tracer?](https://psgraphics.blogspot.com/2022/01/what-is-direct-lighting-next-event.html)
- [Much Ado About Sampling](https://www.jeremyong.com/math/monte%20carlo/2022/05/17/much-ado-about-sampling/)
- [Spatiotemporal reservoir resampling for real-time ray tracing with dynamic direct lighting](https://cs.dartmouth.edu/wjarosz/publications/bitterli20spatiotemporal.html) - combines RIS+MIS with reservoir sampling and demonstrates the reservoir merging capability to perform resampling across space and time

### Intersection
- [Static Object Intersections - Real-Time Rendering Resource Page](https://www.realtimerendering.com/intersections.html) - A collection of intersection algorithms.

### Denoising
- [Ray Tracing Denoising - Alain.xyz](https://alain.xyz/blog/ray-tracing-denoising)
- [Ray Tracing Filtering - Alain.xyz](https://alain.xyz/blog/ray-tracing-filtering)
- [Edge-Avoiding À-Trous Wavelet Transform for fast Global Illumination Filtering](https://jo.dreggn.org/home/2010_atrous.pdf) - Classic paper that introduces a fast and simple filter for real-time ray tracing denoising

### GPU Ray Tracing
See also [APIs](#apis)
- [Megakernels Considered Harmful: Wavefront Path Tracing on GPUs](https://research.nvidia.com/sites/default/files/pubs/2013-07_Megakernels-Considered-Harmful/laine2013hpg_paper.pdf)

## Rasterization
### Graphics Pipeline
- [A trip through the Graphics Pipeline 2011](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index/)
- [Creative Use of GPU Fixed-Function Hardware](https://asawicki.info/news_1745_creative_use_of_gpu_fixed-function_hardware)

### Shading Techniques
- [Graphics Pipelines for Young Bloods](https://www.jeremyong.com/cpp/2021/05/20/graphics-pipelines-for-young-bloods/) - Discuss various tradeoffs between different graphics pipeline techniques
- [A Primer On Efficient Rendering Algorithms & Clustered Shading](https://www.aortiz.me/2018/12/21/CG.html) - Same as the above article but delves deeper with clustered shading

### Culling
- [Optimizing Software Occlusion Culling](https://fgiesen.wordpress.com/2013/02/17/optimizing-sw-occlusion-culling-index/)
- [Nvidia's gl_occlusion_culling example](https://github.com/nvpro-samples/gl_occlusion_culling)

### Depth Buffer
- [Depth Precision Visualized](https://developer.nvidia.com/content/depth-precision-visualized)

### Software Rasterization
- [ssloy/tinyrenderer](https://github.com/ssloy/tinyrenderer) - A short tutorial on writing a software rasterizer. Be careful that the tutorial has some rough edges.
- [A Parallel Algorithm for Polygon Rasterization](https://www.cs.drexel.edu/~david/Classes/Papers/comp175-06-pineda.pdf)
- [Scratchapixel: Rasterization Stage](https://www.scratchapixel.com/lessons/3d-basic-rendering/rasterization-practical-implementation/rasterization-stage)
- [Triangle rasterization in practice](https://fgiesen.wordpress.com/2013/02/08/triangle-rasterization-in-practice/)
- [Optimizing the basic rasterizer](https://fgiesen.wordpress.com/2013/02/10/optimizing-the-basic-rasterizer/)
- [High-Performance Software Rasterization on GPUs](https://users.aalto.fi/~laines9/publications/laine2011hpg_paper.pdf)
- [Line Rasterization slides, MIT EECS 6.837, Teller and Durand](http://groups.csail.mit.edu/graphics/classes/6.837/F02/lectures/6.837-7_Line.pdf)

## Graphics Effects

### Normal Mapping
- [Three Normal Mapping Techniques Explained For the Mathematically Uninclined](https://www.gamedeveloper.com/programming/three-normal-mapping-techniques-explained-for-the-mathematically-uninclined)
- [Normal Mapping - Learn OpenGL](https://learnopengl.com/Advanced-Lighting/Normal-Mapping)

### Hash Functions
-[PCG Family of Hash Functions - Hash Functions for GPU Rendering](https://www.reedbeta.com/blog/hash-functions-for-gpu-rendering/)

### Dithering
-[Dithering on the GPU](http://alex-charlton.com/posts/Dithering_on_the_GPU/) - Dithering for aesthetic purposes.
-[Anisoptera Games - How to Fix Color Banding with Dithering](https://www.anisopteragames.com/how-to-fix-color-banding-with-dithering/) - Dithering for functional purposes (fixing color banding on gradients).

### Shadow
- [Shadow Mapping - LearnOpenGL](https://learnopengl.com/Advanced-Lighting/Shadows/Shadow-Mapping)
- [Percentage-Closer Soft Shadows](https://developer.download.nvidia.com/shaderlibrary/docs/shadow_PCSS.pdf)
- [Efficient Shadows from Many Lights](https://efficientshading.com/wp-content/uploads/s2015_shadows.pdf)
- [Reflective Shadow Maps](https://ericpolman.com/2016/03/17/reflective-shadow-maps/)
- [Experiments in Hybrid Raytraced Shadows](https://interplayoflight.wordpress.com/2021/05/15/experiments-in-hybrid-raytraced-shadows/)
- 🎥 [Michał Olejnik - Raytraced Shadows in Call of Duty: Modern Warfare video presentation](https://www.youtube.com/watch?v=VXp-HEAw-l4)
- [Using Blue Noise For Raytraced Soft Shadows](https://blog.demofox.org/2020/05/16/using-blue-noise-for-raytraced-soft-shadows/)

### Ambient Occlusion
- [Learn OpenGL: SSAO](https://learnopengl.com/Advanced-Lighting/SSAO)
- [John Chapman SSAO Tutorial](http://john-chapman-graphics.blogspot.com/2013/01/ssao-tutorial.html)
- [Screen Space Ambient Occlusion - Louis Bavoil, Miguel Sainz](https://developer.download.nvidia.com/SDK/10.5/direct3d/Source/ScreenSpaceAO/doc/ScreenSpaceAO.pdf)
- [Know your SSAO artifacts](https://mtnphil.wordpress.com/2013/06/26/know-your-ssao-artifacts/)
- [Practical Realtime Strategies for Accurate Indirect Occlusion](https://iryoku.com/downloads/Practical-Realtime-Strategies-for-Accurate-Indirect-Occlusion.pdf)

### Reflection
- [Screen-Space Reflections Explained](https://jhstrom.blogspot.com/2021/03/screen-space-reflections-explained.html)

### Transparency
- [Learn OpenGL: OIT](https://learnopengl.com/Guest-Articles/2020/OIT/Introduction)
- [Compositing digital images](https://graphics.pixar.com/library/Compositing/paper.pdf)
- [Visual glBlendFunc + glBlendEquation Tool](https://www.andersriggelsen.dk/glblendfunc.php)
- Order independent transparency blog series
  - [Part 1](https://interplayoflight.wordpress.com/2022/06/25/order-independent-transparency-part-1/)
  - [Part 2](https://interplayoflight.wordpress.com/2022/07/02/order-independent-transparency-part-2/)
  - [Endgame](https://interplayoflight.wordpress.com/2022/07/10/order-independent-transparency-endgame/)

### Ray Marching and SDF
- [Graphics Codex: Ray Marching](https://graphicscodex.com/app/app.html?page=_rn_rayMrch)
- [Distant functions for primitives - Inigo Quilez](http://iquilezles.org/articles/distfunctions/)
- [soft shadows in raymarched SDFs - 2010](http://iquilezles.org/articles/rmshadows/)

### Line, Edge, and Outline Drawing
#### Triangulated line
- [Drawing Lines is Hard](https://mattdesl.svbtle.com/drawing-lines-is-hard) - Summarizes the problem of GPU line primitives and introduces techniques for drawing triangulated lines.
- [Instanced Line Rendering Part I](https://wwwtyro.net/2019/11/18/instanced-lines.html) - Builds on the foundation from "Drawing Lines is Hard" and uses instance rendering to draw lines.
- [Instanced Line Rendering Part II: Alpha blending](https://wwwtyro.net/2021/10/01/instanced-lines-part-2.html) - Continue of the above article, and introduces a way to do alpha-blending with triangulated lines.

#### Outline
- [5 ways to draw an outline](https://alexanderameye.github.io/notes/rendering-outlines/)
- [The Quest for Very Wide Outlines](https://bgolus.medium.com/the-quest-for-very-wide-outlines-ba82ed442cd9)

### Text Rendering
- [Learn OpenGL: Text Rendering](https://learnopengl.com/In-Practice/Text-Rendering)
- [bitmap font renderer](https://jmickle66666666.github.io/blog/techart/2019/12/18/bitmap-font-renderer.html)

### Tessellation
- [Tutorial 30: Basic Tessellation](https://ogldev.org/www/tutorial30/tutorial30.html)

### Voxel Rendering
- [VoxelSpace](https://github.com/s-macke/VoxelSpace)

### Volume Rendering
- [Structured Volume Sampling](https://github.com/huwb/volsample) - MIT-licensed implementation of the Structured Volume Sampling technique, along with a simple framework for comparing other techniques.

### Dithering
- [Dithering on the GPU](http://alex-charlton.com/posts/Dithering_on_the_GPU/) - describe a novel algorithm for ordered dithering based on an arbitrary palette

### Sprite Rendering
- [Modern (Bindless) Sprite Batch for Vulkan (and more!)](https://jorenjoestar.github.io/post/modern_sprite_batch/)

### Atmosphere Scattering
- [Precomputed Atmospheric Scattering](https://hal.inria.fr/inria-00288758/document)
- [Precomputed Atmospheric Scattering: a New Implementation](https://ebruneton.github.io/precomputed_atmospheric_scattering/)

### Grass Rendering
- [Responsive Real-Time Grass Rendering for General 3D Scenes](https://www.cg.tuwien.ac.at/research/publications/2017/JAHRMANN-2017-RRTG/JAHRMANN-2017-RRTG-draft.pdf)
- [Procedural grass rendering - Outerra](https://outerra.blogspot.com/2012/05/procedural-grass-rendering.html) - Is an inspiration of the following talk
- 🎥 [Procedural Grass in 'Ghost of Tsushima'](https://www.youtube.com/watch?v=Ibe1JBF5i5Y)

## PBR
See also [Assets/Materials](#materials) for PBR materials
- [Physically Based Rendering in Filament](https://google.github.io/filament/Filament.html)
- [PBR - Learn OpenGL](https://learnopengl.com/PBR/Theory)
- [Everything (or most things) wrong with learnopengl.com/PBR/Theory](https://docs.google.com/document/d/1ZLT1-fIek2JkErN9ZPByeac02nWipMbO89oCW2jxzXo/edit)
- [Real Shading in Unreal Engine 4](https://cdn2.unrealengine.com/Resources/files/2013SiggraphPresentationsNotes-26915738.pdf) - discusses the PBR model adopted by Epic Games in their 4th Unreal Engine installment. A large part of Learn OpenGL PBR chapter is adapted from this source
- [Crash Course in BRDF Implementation](https://boksajak.github.io/files/CrashCourseBRDF.pdf)
- [Physically Based Shading at Disney](https://blog.selfshadow.com/publications/s2012-shading-course/burley/s2012_pbs_disney_brdf_notes_v3.pdf)
- [Deriving Lambertian BRDF from first principles](https://sakibsaikia.github.io/graphics/2019/09/10/Deriving-Lambertian-BRDF-From-First-Principles.html)
<!-- markdown-link-check-disable-next-line -->
- [Basics of physically-based rendering](https://www.researchgate.net/publication/262326548_Basics_of_physically-based_rendering)
- [Moving Frostbite to Physically Based Rendering 3.0](https://seblagarde.files.wordpress.com/2015/07/course_notes_moving_frostbite_to_pbr_v32.pdf)

## Textures
### Mipmapping
- [Pyramidal Parametrics](http://www.cs.cmu.edu/afs/cs.cmu.edu/academic/class/15869-f11/www/readings/williams83_mipmap.pdf) - The original Mipmap paper.

### Texture Compression
- [Understanding BCn Texture Compression Formats](https://www.reedbeta.com/blog/understanding-bcn-texture-compression-formats/) - describes a family of lossy hardware-based texture compression formats called BCn

### Texture Bombing
- [GPU Gems Chapter 20. Texture Bombing](https://developer.nvidia.com/gpugems/gpugems/part-iii-materials/chapter-20-texture-bombing)
- [Texture bombing 3 samples](https://www.shadertoy.com/view/4tyGWK) - a shader from Inigo Quilez (modified by huwb) that shows how to perform the GPU Gems technique using 3 texture samples instead of 4! 
- [On Histogram-Preserving Blending for Randomized Texture Tiling](https://jcgt.org/published/0008/04/02/) - attempts to resolve artifacts you get when blending two textures together (also only using 3 texture samples, plus a lookup table per texture

## Shader Programming
- [The Book of Shaders](https://thebookofshaders.com/)
- [shadertoy smoothstep demo](https://www.shadertoy.com/view/sdyGRW)
- [Shader Derivative Functions](http://www.aclockworkberry.com/shader-derivative-functions/) - Useful for normals.
- [How to read shader assembly](https://interplayoflight.wordpress.com/2021/04/18/how-to-read-shader-assembly/)
- [ShaderToy Advanced Tricks](https://shadertoyunofficial.wordpress.com/2021/03/09/advanced-tricks/) 

## Compute
### Introduction to compute shader
- [Introduction to Compute Shaders](https://anteru.net/blog/2018/intro-to-compute-shaders/)
- [More Compute Shaders](https://anteru.net/blog/2018/more-compute-shaders/)
- [Even more Compute Shaders](https://anteru.net/blog/2018/even-more-compute-shaders/)
- [Compute Shader Glossary](https://github.com/googlefonts/compute-shader-101/blob/main/docs/glossary.md)

### GPU Architecture
- 🎥 [CIS 565 GPU Programming and Architecture](http://cis565-fall-2021.github.io/) - A course that introduce parallel programming with a Computer Graphics flavor.
- [Gentle introduction to GPUs inner workings](https://vksegfault.github.io/posts/gentle-intro-gpu-inner-workings/) - This article summarizes some lower-level aspects of how GPU executes. It uses the Vulkan API terminology, but the concept is largely platform-independent.
- [GCN – two ways of latency hiding and wave occupancy](https://bartwronski.com/2014/03/27/gcn-two-ways-of-latency-hiding-and-wave-occupancy/)
- [Breaking Down Barriers](https://therealmjp.github.io/posts/breaking-down-barriers-part-1-whats-a-barrier/)
- [How does a GPU Shader work?](https://aras-p.info/texts/files/2018Academy%20-%20GPU.pdf)
- [Compute Shaders: Optimize your engine using compute / Lou Kramer, AMD](https://www.youtube.com/watch?v=0DLOJPSxJEg) 
<!-- markdown-link-check-disable-next-line -->
- [RDNA Architecture Whitepaper](https://www.amd.com/system/files/documents/rdna-whitepaper.pdf)
- [AMU RDNA2 Performance guide](https://gpuopen.com/performance/)
- [The Peak-Performance-Percentage Analysis Method for Optimizing Any GPU Workload](https://developer.nvidia.com/blog/the-peak-performance-analysis-method-for-optimizing-any-gpu-workload/)
- [[video] All the Pipelines - Journey through the GPU](https://gpuopen.com/videos/graphics-pipeline/)

### Parallel Algorithms
- [Parallel Prefix Sum (Scan) with CUDA](http://www.eecs.umich.edu/courses/eecs570/hw/parprefix.pdf)
- [Thinking Parallel, Part I: Collision Detection on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-i-collision-detection-gpu/)
- [Thinking Parallel, Part II: Tree Traversal on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-ii-tree-traversal-gpu/)
- [Thinking Parallel, Part III: Tree Construction on the GPU](https://developer.nvidia.com/blog/thinking-parallel-part-iii-tree-construction-gpu/)

### Atomics
- [CUDA Pro Tip: Optimized Filtering with Warp-Aggregated Atomics](https://developer.nvidia.com/blog/cuda-pro-tip-optimized-filtering-warp-aggregated-atomics/)

## Color, HDR, and Tone Mapping
- [Supporting Native HDR Monitors - OurMachinery](https://ruby0x1.github.io/machinery_blog_archive/post/supporting-native-hdr-monitors/index.html)
- [Introduction to Color Theory for Games, Art and Tech - Shahriar Shahrabi](https://shahriyarshahrabi.medium.com/introduction-to-color-theory-for-games-art-and-tech-67bd4c8607d7)
- [Tone Mapping](https://64.github.io/tonemapping/) - Introduces the theory of Tone Mapping and talks about some commonly used Tone Mapping Operators

## Sampling and anti-aliasing
See also [Ray Tracing/Sampling & Variance Reduction](#sampling--variance-reduction)
- [A Pixel is not a Little Square!](http://alvyray.com/Memos/CG/Microsoft/6_pixel.pdf) - Classic paper on misconception of "a pixel is a little square." It also serves as an introduction to sampling.
- [Basics of Image Resampling](https://entropymine.com/imageworsener/resample/)
- [Computing the Discrepancy with Applications to Supersampling Patterns](http://mentallandscape.com/Papers_tog96.pdf)
- [Generating Antialiased Images at Low Sampling Densities](http://mentallandscape.com/Papers_siggraph87.pdf)
- [Temporal Anti Aliasing – Step by Step](https://ziyadbarakat.wordpress.com/2020/07/28/temporal-anti-aliasing-step-by-step/)
- [The Accumulation Buffer: Hardware Support for High-Quality Rendering (SIGGRAPH 1990)](https://graphics.stanford.edu/courses/cs248-02/haeberli-akeley-accumulation-buffer-sig90.pdf)

## Animation
- [Learn OpenGL: Skeletal Animation](https://learnopengl.com/Guest-Articles/2020/Skeletal-Animation)
- 🎥 [Animation Programming Basics](https://youtu.be/Jkv0pbp0ckQ)
- 🎥 [Animation Graphs](https://youtu.be/R-T3Mk5oDHI)
- [Skeletal animation in glTF](https://lisyarus.github.io/blog/graphics/2023/07/03/gltf-animation.html)

## Geometry
### Geometry representations
- 🎥 [Lecture 10: Meshes and Manifolds (CMU 15-462/662)](https://youtu.be/HePDHsp8spU) - Great overview, and also spend significant time on the half-edge data structure

### Iso-surface methods
- [Interactive explanation of marching cubes and dual contouring](https://wordsandbuttons.online/interactive_explanation_of_marching_cubes_and_dual_contouring.html)
- [Polygonising a scalar field (Marching Cubes)](http://paulbourke.net/geometry/polygonise/)
- [Dual Contouring Tutorial](https://www.boristhebrave.com/2018/04/15/dual-contouring-tutorial/)
- [The Transvoxel Algorithm](https://transvoxel.org/)

### Libraries
- [Geometry Central](https://geometry-central.net/) - A modern C++ library of data structures and algorithms for geometry processing, with a particular focus on surface meshes.

## Physics and Simulation
### Physics-Based Animation
- 🎥 [SIGGRAPH University 2019 Course - An Introduction to Physics-Based Animation](https://youtu.be/b_WJ-HwalwU) - A three-hour fast-paced introduction to Physics-Based Animation
- 🎥 [CSC417/CSC2549-Physics-based Animation Fall 2021](https://youtube.com/playlist?list=PLTkE7n2CwG_PH09_q0Q7ttjqE2F9yGeM3) - Introductory lecture for a course in physics-based animation.

### Attractors
- [Strange Attractors on the GPU series](https://observablehq.com/@rreusser/strange-attractors-on-the-gpu-part-1?collection=@rreusser/writeups)

### Optics
- [Make Your Bokeh Fascinating + related SIGGRAPH 2015 Course](https://research.tri-ace.com/s2015.html) + [Video Recordings](https://dl.acm.org/doi/10.1145/2776880.2792715)

## APIs
### Ray Tracing API
- [The RTX Shader Binding Table Three Ways](https://www.willusher.io/graphics/2019/11/20/the-sbt-three-ways) - Talks about shader binding table with RX12, Vulkan, and Optix
- Chapter 15 "The Shader Binding Table Demystified" of [Ray Tracing Gems II](https://www.realtimerendering.com/raytracinggems/rtg2/index.html) - An extension for the above article

### OpenGL
- [docs.gl](http://docs.gl/) - OpenGL API Documentation.
- [GLConstantsTranslator](https://javagl.github.io/GLConstantsTranslator/GLConstantsTranslator.html) - This page has the names of most OpenGL constants with their respective decimal and hex values. It is useful when certain functions return GL constants.

#### Tutorials
- [Learn OpenGL](https://learnopengl.com/) - The highly recommended tutorial.

#### Meta-links
- [Awesome OpenGL](https://project-awesome.org/eug/awesome-opengl) - Curated List for OpenGL.

#### Best Practices
- [Using Modern OpenGL to Avoid Common Errors](https://juandiegomontoya.github.io/modern_opengl.html) - Talks about using features of post-4.2 OpenGL

### Vulkan
- [Spec](https://www.khronos.org/registry/vulkan/specs/1.2-extensions/html/index.html) - It is a good idea to keep it open while doing Vulkan Programming.
#### Tutorials
- [Vulkan Guide](https://vkguide.dev/) - The best "Vulkan Tutorial" available.
- 🎥 [TU Wien: Vulkan Lecture Series](https://www.youtube.com/playlist?list=PLmIqTlJ6KsE1Jx5HV4sd2jOe3V1KMHHgn)
- [vk_mini_path_tracer tutorial](https://github.com/nvpro-samples/vk_mini_path_tracer) - A relatively small tutorial that focuses on path tracing using Vulkan's ray tracing API.
- [3D Graphics Rendering Cookbook](https://www.amazon.com/Graphics-Rendering-Cookbook-comprehensive-algorithms/dp/1838986197)

#### Meta-links
- [Awesome Vulkan](https://github.com/vinjn/awesome-vulkan)
- [Great Resources - Vulkan Guide](https://vkguide.dev/docs/great_resources)

#### Swapchain & frame resources<!-- markdown-link-check-disable-next-line -->
- [API without Secrets: The Practical Approach to Vulkan* - Part 1](https://www.intel.com/content/www/us/en/developer/articles/training/practical-approach-to-vulkan-part-1.html) (there is no part 2)

#### Renderpass & Dynamic Rendering
- [VK_KHR_dynamic_rendering tutorial](https://lesleylai.info/en/vk-khr-dynamic-rendering/) - A tutorial to Vulkan's dynamic rendering extension
- [Khronos: Streamlining Render Passes](https://www.khronos.org/blog/streamlining-render-passes) - Introduces the [VK_KHR_dynamic_rendering](https://registry.khronos.org/vulkan/specs/1.3-extensions/man/html/VK_KHR_dynamic_rendering.html) extension.

#### Bindless/Descriptor indexing
- 🎥 [Khronos Talk on Descriptor Indexing](https://www.youtube.com/watch?v=tXipcoeuNh4)
- [Vulkan Descriptor Indexing for Mobile](https://community.arm.com/developer/tools-software/graphics/b/blog/posts/vulkan-descriptor-indexing)
- [OurMachinery's Moving The Machinery to Bindless](https://ruby0x1.github.io/machinery_blog_archive/post/moving-the-machinery-to-bindless/index.html)
- [Wicked Engine: Bindless Descriptors](https://wickedengine.net/2021/04/06/bindless-descriptors/)
- [DethRaid's Vulkan Descriptor Indexing](https://gist.github.com/DethRaid/0171f3cfcce51950ee4ef96c64f59617)
- [A note on Descriptor Indexing](https://chunkstories.xyz/blog/a-note-on-descriptor-indexing/)
- [Vulkan Pills 1: Bindless Textures](https://jorenjoestar.github.io/post/vulkan_bindless_texture/)

#### Synchronization
- [TheMaister's Yet another blog explaining Vulkan synchronization](https://themaister.net/blog/2019/08/14/yet-another-blog-explaining-vulkan-synchronization/)
- [Understanding Vulkan Synchronization](https://www.khronos.org/blog/understanding-vulkan-synchronization)
- [Vulkan Timeline Semaphores](https://www.khronos.org/blog/vulkan-timeline-semaphores)

#### Vulkan Compute
- [A simple Vulkan Compute example](https://www.duskborn.com/posts/a-simple-vulkan-compute-example/)
- [Vulkan Subgroup tutorial. AKA wavefronts](https://www.khronos.org/blog/vulkan-subgroup-tutorial)

#### Libraries
- [vk-bootstrap](https://github.com/charles-lunarg/vk-bootstrap) - Library that simplifies the Vulkan initialization boilerplate.
- [VulkanMemoryAllocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) - Memory allocation library that simplifies Vulkan memory allocation and provides decent performance.
- [volk](https://github.com/zeux/volk) - Meta-loader for Vulkan that allows you to dynamically load entry points required to use Vulkan. It also simplifies the use of Vulkan extensions.
- [SPIRV-Reflect](https://github.com/KhronosGroup/SPIRV-Reflect) - Can be used to extract descriptors and push constant information from SPIRV.

#### Performance Best Practice
- [Writing an efficient Vulkan renderer](https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/)

#### Others
- [Vulkan Diagram](https://github.com/David-DiGioia/vulkan-diagrams)

### DirectX 12
- [Reader Question Answered 1 - Learning D3D12](https://www.jendrikillner.com/post/d3d12-learning-plan/) - A roadmap for learning DirectX 12
- [Raw DirectX 12](https://alain.xyz/blog/raw-directx12) - An introduction to writing a simple Hello Triangle DirectX 12 application.
- [Learning DirectX 12](https://www.3dgep.com/learning-directx-12-1/)
- [Direct3D 12 programming guide](https://docs.microsoft.com/en-us/windows/win32/direct3d12/directx-12-programming-guide)

#### Resource Binding & Bindless
- [Resource Binding - Direct3D 12 Programming Guide](https://docs.microsoft.com/en-us/windows/win32/direct3d12/resource-binding)
- [Bindless Texturing for Deferred Rendering and Decals](https://mynameismjp.wordpress.com/2016/03/25/bindless-texturing-for-deferred-rendering-and-decals/)
- [Binding Bindlessly](https://alextardif.com/Bindless.html)
- [Wicked Engine: Bindless Descriptors](https://wickedengine.net/2021/04/06/bindless-descriptors/)

### WebGL
- [Awesome WebGL](https://project-awesome.org/sjfricke/awesome-webgl)

### WebGPU
- [Spec](https://gpuweb.github.io/gpuweb/)
#### Tutorials
- [Learn wgpu](https://sotrh.github.io/learn-wgpu/) - Tutorial of WebGPU API using Rust and the wgpu library.

## System Design
### Renderer Architecture
- 🎥 [SIGGRAPH 2021 REAC: Unity Rendering Architecture](https://www.youtube.com/watch?v=6LzcXPIWUbc)
- [Efficiently rendering glTF models](https://toji.github.io/webgpu-gltf-case-study/) - A case study on how to design a renderer under modern graphics APIs that can take diverse input

### GPU-driven rendering
- [GPU Driven Rendering - Siggraph 2015](http://advances.realtimerendering.com/s2015/aaltonenhaar_siggraph2015_combined_final_footer_220dpi.pdf)

## Scene Description
- [Siggraph 2019 Hydra](https://graphics.pixar.com/usd/files/Siggraph2019_Hydra.pdf) - Presentation slides for Hydra, which is an open-source framework to transport live scene graph data to renderers.

## General Programming
### Meta-links
- [Awesome C](https://project-awesome.org/inputsh/awesome-c#game-programming)
- [Awesome C++](https://project-awesome.org/fffaraz/awesome-cpp)
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust)
### Engine Development
- [Game Engine Architecture](https://www.gameenginebook.com/) (paid book)
- [The Shader Permutation Problem - Part 1: How Did We Get Here?](https://therealmjp.github.io/posts/shader-permutations-part1/)
- [The Shader Permutation Problem - Part 2: How Do We Fix It?](https://therealmjp.github.io/posts/shader-permutations-part2/)
### Performance Optimization
- [Algorithms for Modern Hardware](https://en.algorithmica.org/hpc/) - This book contains great info on getting the best performance by looking at the actual hardware.
### High-level Programming
- [Game Programming Patterns](http://gameprogrammingpatterns.com/)
### Game loop
- [Game Loop - Game Programming Patterns](http://gameprogrammingpatterns.com/game-loop.html)
- [Fix Your Timestep!](https://gafferongames.com/post/fix_your_timestep/)
- Chapter 8 "The Game Loop and Real-Time Simulation" of Game Engine Architecture

### Floating-point numbers
- [Onboarding floating-point](https://www.altdevarts.com/p/onboarding-floating-point) - A series about floating-point numbers by Mike Acton
- [Floating-point in mobile shaders](https://solidpixel.github.io/2021/11/23/floats_in_shaders.html)

### Memory Allocation & Management
- [Memory Allocation Strategies series](https://www.gingerbill.org/series/memory-allocation-strategies/)
- [Memory Management section on Pbrt](https://www.pbr-book.org/3ed-2018/Utilities/Memory_Management)
- The Memory chapter of Game Engine Architecture
- [Object Pool](http://gameprogrammingpatterns.com/object-pool.html) chapter of Game Programming Pattern.
- 🎥 CppCon 2017: John Lakos “Local ('Arena') Memory Allocators” [[Part1]](https://youtu.be/nZNd5FjSquk) [[Part2]](https://youtu.be/CFzuFNSpycI)
- 🎥 [CppCon 2017: Bob Steagall “How to Write a Custom Allocator”](https://youtu.be/kSWfushlvB8)

## Tools/libraries

### Debuggers
- [RenderDoc](https://renderdoc.org/)
- [Nvidia Nsight Graphics](https://developer.nvidia.com/nsight-graphics)
- [Radeon™ GPU Profiler (AMD)](https://github.com/GPUOpen-Tools/radeon_gpu_profiler)<!-- markdown-link-check-disable-next-line -->
- [Intel® GPA](https://www.intel.com/content/www/us/en/developer/tools/graphics-performance-analyzers/overview.html)
- [SpectorJS (WebGL)](https://github.com/BabylonJS/Spector.js)

### Profilers
A bunch of graphics debuggers above also have profiling capabilities.
- [Optick: C++ Profiler For Games](https://github.com/bombomby/optick)
- [Tracy Profiler](https://github.com/wolfpld/tracy)
- [Dear Imgui profiler widget](https://github.com/Raikiri/LegitProfiler)

### Denoiser
- [Optix Denoiser](https://developer.nvidia.com/optix-denoiser)
- [FidelityFX-Denoiser](https://github.com/GPUOpen-Effects/FidelityFX-Denoiser)
- [Open Image AI Denoiser](https://github.com/OpenImageDenoise/oidn)

## Assets
### Polygonal Model & Scene
- [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html) - OBJ format scenes.
- [ORCA: Open Research Content Archive](https://developer.nvidia.com/orca) - Free large graphics scene samples.
- [Rendering Resources - Benedikt Bitterli](https://benedikt-bitterli.me/resources/) - Scenes in Tungsten, Mitsuba, and pbrt-v3 formats.
- [NASA 3D Resources](https://nasa3d.arc.nasa.gov/models/) - Some assets of satellites, celestial bodies, etc. Various formats.
- [Three Dimensional Scans](https://threedscans.com/) - some three-dimensional scans of animals and statues.
- [Stanford 3D Scanning Repository](http://graphics.stanford.edu/data/3Dscanrep/) - a bunch of scanned reconstructions
- [The Base Mesh](https://thebasemesh.com/) - CC0 mesh collection
- [PolyHaven](https://polyhaven.com/) - Public 3d asset library, also CC0
- [MIT CSAIL Sample OBJ Models](https://groups.csail.mit.edu/graphics/classes/6.837/F03/models/) - A couple of models provided by MIT<!-- markdown-link-check-disable-next-line -->
- [Intel Sponza and Graphics Research Samples Library](https://www.intel.com/content/www/us/en/developer/topic-technology/graphics-research/samples.html) - Intel's revamped high-resolution Sponza model and a couple of related pieces
- [KhronosGroup glTF Sample Models](https://github.com/KhronosGroup/glTF-Sample-Models)
- [Quaternius Free Game Assets](https://quaternius.com/tutorials.html) - Low poly models, CC0

### Materials
- [ambientCG](https://ambientcg.com/) - Public Domain materials for Physically Based Rendering.
- [Physically Based](https://physicallybased.info/) - A database of physically based values for CG artists

### Voxel Data
- [TU Wien Volume Data](https://www.cg.tuwien.ac.at/research/publications/2005/dataset-stagbeetle/) - Listed in their collection of publications.
- [Open Scientific Visualization Datasets](https://klacansky.com/open-scivis-datasets/) - Large collection of CT scans of various objects.
- [Stanford Volume Archive](https://www-graphics.stanford.edu/data/voldata/) - Several volume datasets (CT/MRI).
- [MorphoSource](https://www.morphosource.org) - Enormous library of 2D and 3D data, mesh and voxel, of biological samples and cultural objects.
- [Osirix MANIX and other test DICOMs](https://www.osirix-viewer.com/resources/dicom-image-library/)



# Books <a id="books2"></a>

## Jendrik Illner reading list
https://www.jendrikillner.com/post/reading-list/

## 3D Math Primer for Graphics and Game Development - 2011
https://gamemath.com/

## Foundations of game engine development - Mathematics (2016)
https://foundationsofgameenginedev.com/

## Foundations of game engine development - Rendering (2019)
https://foundationsofgameenginedev.com/

## Real-Time Rendering 4th Edition
https://www.realtimerendering.com/

## Ray tracing in a weekend series
https://raytracing.github.io/

## PBRT
https://pbrt.org/

## Computer Graphics - Principles and Practice
https://www.amazon.com.au/Computer-Graphics-Principles-Practice-Practices/dp/0321399528

## Fundamentals of Computer Graphics (2021)
https://www.amazon.com.au/Fundamentals-Computer-Graphics-Steve-Marschner-dp-0367505037/dp/0367505037

## ShaderX/GPU Pro/GPU Zen Books
https://www.realtimerendering.com/resources/shaderx/

## GPU Gems
https://developer.nvidia.com/gpugems/gpugems/contributors

## Raytracing Gems
https://www.realtimerendering.com/raytracinggems/

# Real-time rendering portal <a id="real-time-rendering-portal"></a>
https://www.realtimerendering.com/portal.html

- Contains a list of useful courses, books, conference notes, and more.