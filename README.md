# Graphics programming links
This document contains a large list of graphics programming links I found from some brief googling. This document is incredibly useful when conducting research before implementing a graphics technique in code as there are so many unique ways different tech demos and games tackle the same graphics problems. Many techniques are also buried in the web, so having a consolidated searchable list helps immensely.

This list was put together quickly, so links from different topics and authors are not combined together.

# Table of contents
1. [Graphics programming virtual meetup (GPVM)](#gpvm)
2. [[README#Kosua20]]
3. [Books](#books)
    1. [Jendrik Illner](#jendrik)

## Graphics programming virtual meetup list <a id="gpvm"></a>
https://github.com/Graphics-Programming-Virtual-Meetup/resources?tab=readme-ov-file

## Kosua20
https://gist.github.com/kosua20/a337366c6fd2871f73022da8e69e8b76#motion-blur

# Render

## Animation

### Skinning
- https://blog.traverseresearch.nl/ray-tracing-animated-crowds-bc0e775c74ad  

## Antialiasing
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

## Blending
- https://github.com/dtrebilco/PreMulAlpha  
- https://tylerxhobbs.com/essays/2017/a-generative-approach-to-simulating-watercolor-paints  

## Compression
- http://aras-p.info/texts/CompactNormalStorage.html  
- https://bartwronski.com/2017/04/02/small-float-formats-r11g11b10f-precision/  
- https://shaneycg.github.io/ducktales-remastered-texture-compression/  
- http://www.intrinsic-engine.com/reverse-z-cheat-sheet/  
- http://www.reedbeta.com/blog/understanding-bcn-texture-compression-formats/  
- https://www.yosoygames.com.ar/wp/2018/03/vertex-formats-part-1-compression/  

## Dithering
- https://bartwronski.com/2016/10/30/dithering-in-games-mini-series/  
- https://blog.frost.kiwi/GLSL-noise-and-radial-gradient/  
- https://loopit.dk/banding_in_games.pdf  
- http://www.visualextract.com/posts/color-banding/  

## Dof
- https://blog.voxagon.se/2018/05/04/bokeh-depth-of-field-in-single-pass.html  

## Geometry
- https://dubiousconst282.github.io/2024/10/03/voxel-ray-tracing/  
- https://jglrxavpok.github.io/2024/01/19/recreating-nanite-lod-generation.html  
- https://jglrxavpok.github.io/2024/08/21/recreating-nanite-raytracing.html  
- https://jms55.github.io/posts/2024-06-09-virtual-geometry-bevy-0-14/  
- https://nickmcd.me/2021/04/04/high-performance-voxel-engine/  
- https://people.engr.tamu.edu/schaefer/research/iso_simplicial.pdf  
- https://themaister.net/blog/2024/01/17/modernizing-granites-mesh-rendering/  
- https://www.jakelow.com/blog/hobby-curves  
- https://www.willusher.io/graphics/2024/04/22/webgpu-marching-cubes  

## Gpu
- https://poniesandlight.co.uk/reflect/bitonic_merge_sort/  

### Sorting
- https://linebender.org/wiki/gpu/sorting/  

## Hdr
- https://bartwronski.com/2016/08/29/localized-tonemapping/  
- http://filmicworlds.com/blog/minimal-color-grading-tools/  
- https://john-chapman.github.io/2017/08/23/dynamic-local-exposure.html  
- https://wolf.nereid.pl/posts/image-viewer/#fnref:26  

## Lens flare
- http://bitsquid.blogspot.com/2017/07/physically-based-lens-flare.html  
- http://john-chapman-graphics.blogspot.com/2013/02/pseudo-lens-flare.html  

## Lighting
- https://aaltodoc.aalto.fi/server/api/core/bitstreams/ab0d594b-da79-4402-88ca-3811b39745e6/content  

### Brdf
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

### Gi
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

### Ibl
- http://blog.hvidtfeldts.net/index.php/2012/10/image-based-lighting/  
- https://chetanjags.wordpress.com/2015/08/26/image-based-lighting/  
- https://elalish.blogspot.com/2020/11/environment-lighting.html  
- https://interplayoflight.wordpress.com/2013/04/29/parallax-corrected-cubemapping-with-any-cubemap/  
- https://seblagarde.wordpress.com/2012/06/10/amd-cubemapgen-for-physically-based-rendering/  
- https://seblagarde.wordpress.com/2012/09/29/image-based-lighting-approaches-and-parallax-corrected-cubemap/  
- http://www.trentreed.net/blog/physically-based-shading-and-image-based-lighting/  
- http://xlgames-inc.github.io/posts/improvedibl/  

### Light
- http://blog.magnum.graphics/guest-posts/area-lights-with-ltcs/  
- https://ciechanow.ski/lights-and-shadows/  
- http://www.elopezr.com/rendering-line-lights/  

### Shading
- http://artisaverb.info/PBT.html  
- http://blog.selfshadow.com/2011/07/22/specular-showdown/  
- https://ivokabel.github.io/2018/05/15/rendering-layered-materials.html  
- http://renderwonk.com/publications/s2010-shading-course/hoffman/s2010_physically_based_shading_hoffman_a_notes.pdf  
- https://seblagarde.files.wordpress.com/2015/07/course_notes_moving_frostbite_to_pbr_v32.pdf  
- https://seblagarde.wordpress.com/tag/physically-based-rendering/  
- http://www.alexandre-pestana.com/physically-based-rendering-viewer/  
- http://www.crytek.com/download/2014_03_25_CRYENGINE_GDC_Schultz.pdf  
- https://www.khronos.org/webgl/wiki_1_15/images/2016-07-28_WebGL_BOF_PBR.pdf  

## Lod
- https://shaderbits.com/blog/octahedral-impostors/  

## Motion blur
- http://john-chapman-graphics.blogspot.com/2013/01/per-object-motion-blur.html  

## Normal mapping
- http://apoorvaj.io/exploring-bump-mapping-with-webgl.html  
- http://blog.selfshadow.com/publications/blending-in-detail/  
- https://casual-effects.com/research/McGuire2005Parallax/index.html  
- https://developer.amd.com/wordpress/media/2012/10/Tatarchuk-ParallaxOcclusionMapping-Sketch-print.pdf  
- https://learnopengl.com/Advanced-Lighting/Parallax-Mapping  
- https://marmosetco.tumblr.com/post/81245981087  
- http://sunandblackcat.com/tipFullView.php?l=eng&topicid=28  

## Path tracing
- https://graphics.pixar.com/library/RendermanTog2018/paper.pdf  

## Pipeline
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

### Shading
- https://therealmjp.github.io/posts/light-indexed-deferred-rendering/  
- https://www.cse.chalmers.se/~uffe/clustered_shading_preprint.pdf  
- https://www.realtimerendering.com/blog/deferred-lighting-approaches/  

## Point cloud
- https://www.magnopus.com/blog/how-we-render-extremely-large-point-clouds  

## Postprocess
- https://blog.maximeheckel.com/posts/on-crafting-painterly-shaders/  

## Procedural

### Vegetation
- https://medium.com/@kacper.szwajka842/gpu-run-time-procedural-placement-on-terrain-cc874e39bbfb  

## Rasterization
- http://chrishecker.com/Miscellaneous_Technical_Articles  
- https://fgiesen.wordpress.com/2013/02/10/optimizing-the-basic-rasterizer/  
- https://github.com/ssloy/tinyrenderer/wiki  
- https://media.contentapi.ea.com/content/dam/ea/seed/presentations/seed-coverage-bitmasks-mittring.pdf  
- http://www.cbloom.com/3d/techdocs/pipeline.txt  
- https://www.scratchapixel.com/lessons/3d-basic-rendering/rasterization-practical-implementation/visibility-problem-depth-buffer-depth-interpolation  

## Ray tracing
- http://blog.hvidtfeldts.net/index.php/category/raytracing/  
- https://blog.yiningkarlli.com/2018/10/bidirectional-mipmap.html  
- https://diharaw.github.io/post/adventures_in_hybrid_rendering/  
- https://gist.github.com/h3r2tic/ba39300c2b2ca4d9ca5f6ff22350a037  
- http://hughsk.io/fragment-foundry/chapters/01-hello-world.html  
- http://jamie-wong.com/2016/07/15/ray-marching-signed-distance-functions/  
- https://reindernijhoff.net/2019/03/wolfenstein-raytracing-on-using-webgl1/  
- https://www.osar.fr/notes/logspherical/  
- https://www.tylermw.com/throwing-shade/  

## Raymarching
- https://jarllarsson.github.io/gen/gunkraymarcher.html  

## Sampling
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

## Screenspace

### Ao
- https://frictionalgames.blogspot.com/2014/01/tech-feature-ssao-and-temporal-blur.html  
- http://john-chapman-graphics.blogspot.com/2013/01/ssao-tutorial.html  
- https://ktstephano.github.io/rendering/stratusgfx/svsm  
- https://mtnphil.wordpress.com/2013/06/26/know-your-ssao-artifacts/  
- https://panoskarabelas.com/posts/screen_space_shadows/  
- http://www.derschmale.com/2013/12/20/an-alternative-implementation-for-hbao-2/  

### Reflection
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

### Ssr
- https://zznewclear13.github.io/posts/screen-space-reflection-en/  

## Sdf
- https://blog.demofox.org/2016/02/29/fast-voronoi-diagrams-and-distance-dield-textures-on-the-gpu-with-the-jump-flooding-algorithm/  
- https://iquilezles.org/articles/  
- http://litherum.blogspot.com/2015/02/end-to-end-tour-of-text-rendering.html?m=1  
- https://redpenguin101.github.io/html/posts/2025_01_21_voronoi.html  

## Shader

### 2d
- https://bgolus.medium.com/the-best-darn-grid-shader-yet-727f9278b9d8  

## Shadow
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

## Snow
- https://www.gdcvault.com/play/1020177/Deformable-Snow-Rendering-in-Batman  

## Stereogram
- https://developer.nvidia.com/gpugems/GPUGems/gpugems_ch41.html  

## Swapchain
- https://erfan-ahmadi.github.io/blog/Nabla/fif  
- https://marcelbraghetto.github.io/a-simple-triangle/2019/07/27/part-24/  
- https://martinfullerblog.wordpress.com/2023/10/11/dynamic-resolution-scaling-drs-implementation-best-practice/  
- https://medium.com/@tglaiel/how-to-make-your-game-run-at-60fps-24c61210fe75  

### Vsync
- https://raphlinus.github.io/ui/graphics/gpu/2021/10/22/swapchain-frame-pacing.html  
- https://www.intel.com/content/www/us/en/developer/articles/code-sample/sample-application-for-direct3d-12-flip-model-swap-chains.html  

## Vfx
- https://housemarque.com/news/2021/9/15/returnal-vfx-breakdown  

## Visibility
- https://bazhenovc.github.io/blog/post/gpu-driven-occlusion-culling-slides-lif/  
- https://fgiesen.wordpress.com/2010/10/17/view-frustum-culling/  
- https://interplayoflight.wordpress.com/2017/11/15/experiments-in-gpu-based-occlusion-culling/  
- https://zeuxcg.org/2009/01/31/view-frustum-culling-optimization-introduction/  
- https://zeuxcg.org/2009/01/31/view-frustum-culling-optimization-introduction/  

## Volumetric
- https://arxiv.org/abs/1612.04336  
- https://chuckleplant.github.io/2017/05/28/light-shafts.html  
- https://ebruneton.github.io/precomputed_atmospheric_scattering/  
- https://github.com/ebruneton/clear-sky-models  
- https://slsdo.github.io/volumetric-cloud/  
- http://www.eugenedeon.com/wp-content/uploads/2021/11/hitchhiker_v0.3_graphics.pdf  
- https://www.guerrilla-games.com/read/the-real-time-volumetric-cloudscapes-of-horizon-zero-dawn  
- http://www.thetenthplanet.de/archives/4519  

## Water
- https://auzaiffe.wordpress.com/2024/08/08/mapping-ffts-to-a-sphere-an-unexpected-journey/  
- https://gikster.dev/posts/Ocean-Simulation/  
- https://medium.com/@evanwallace/rendering-realtime-caustics-in-webgl-2a99a29a0b2c  
- https://seblagarde.wordpress.com/2012/12/10/observe-rainy-world/  
- https://web.archive.org/web/20111113000538/http://www.gamasutra.com/gdce/2001/jensen/jensen_04.htm  
- https://web.archive.org/web/20180315084809/https://community.eidosmontreal.com/blogs/hitman-ocean-tech  
- https://www.fxguide.com/featured/assassins-creed-iii-the-tech-behind-or-beneath-the-action/  
- https://www.gamasutra.com/blogs/PavelZagrebelnyy/20171116/309626/Mud_and_Water_of_SpintiresMudRunner.php  

# Gpu
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

## Debug
- https://vksegfault.github.io/posts/gentle-intro-gpu-inner-workings/  

## Dx12
- https://alextardif.com/DX12Tutorial.html  
- https://digitalerr0r.net/2015/08/19/quickstart-directx-12-programming/  
- http://diligentgraphics.com/diligent-engine/architecture/d3d12/  
- https://docs.microsoft.com/en-us/windows/win32/direct3d12/directx-12-programming-guide  
- https://www.3dgep.com/learning-directx-12-1/  

## Hardware
- https://86box.net/2025/02/25/riva128-part-1.html#fnref:mipmap  

## Maths
- https://theorangeduck.com/page/closed-form-matrix-decompositions  

## Performance
- https://gpu-primitives-course.github.io/  

## Pipeline
- https://timur.hu/blog/2022/mesh-and-task-shaders  

## Security
- https://chromium.googlesource.com/chromium/src/+/main/docs/security/research/graphics/webgpu_technical_report.md  

## Shader

### Compiler
- https://devlog.hexops.com/2024/building-the-directx-shader-compiler-better-than-microsoft/  

## Thread
- https://logins.github.io/programming/2020/12/31/RenderThreadJobification.html  

## Vulkan
- https://alain.xyz/blog/raw-vulkan#overview  
- http://anki3d.org/porting-anki-to-vulkan/  
- https://blog.nap-labs.tech/d0/dfd/md_articles_001_nap_opengl_to_vulkan  
- https://github.com/David-DiGioia/vulkan-diagrams  
- https://github.com/diharaw/hybrid-rendering  
- http://themaister.net/blog/2019/04/20/a-tour-of-granites-vulkan-backend-part-3/  
- https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf  
- https://zeux.io/2019/07/17/serializing-pipeline-cache/  
- https://zeux.io/2020/02/27/writing-an-efficient-vulkan-renderer/  

## Webgpu
- https://floooh.github.io/2023/10/16/sokol-webgpu.html  

# Prog
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

## Arm
- https://blog.yiningkarlli.com/2021/05/porting-takua-to-arm-pt1.html  

## Assembly
- https://mariokartwii.com/armv8/  

## Build
- https://eli.thegreenplace.net/2013/07/09/library-order-in-static-linking  
- https://mcyoung.xyz/2021/06/01/linker-script/  

## Demoscene
- https://6octaves.blogspot.com/2017/06/interview-with-japanese-demoscener.html?m=1  
- https://alia-traces.github.io/demoscene/metal/pathtracing/2020/07/24/reconstruction.html  
- https://docs.google.com/presentation/d/1RWzos-3yguFRVSveNPu4vN7b5BQWjcKEjcdrB5u2okE/mobilepresent?slide=id.g3de4468ac9_0_661  
- https://gargaj.tumblr.com/post/178117551485/along-for-the-ride-a-reasonably-complex-demo  
- https://github.com/runestubbe/Crinkler  
- https://in4k.github.io/  
- https://medium.com/@jerry.ylilammi/making-of-newton-protocol-e9ccde41af30  
- http://www.amietia.com/oscarschair.html  
- http://www.lofibucket.com/articles/64k_intro.html  

## Font
- https://gwern.net/sidenote  

## Fun
- https://eieio.games/nonsense/game-11-flappy-bird-finder/#fnref:4  
- https://www.dangermouse.net/esoteric/piet.html  

## Hardware
- https://ctf.re/windows/kernel/pcie/tutorial/2023/02/14/pcie-part-1/  

## Kinect
- http://blog.nelga.com/setup-microsoft-kinect-on-mac-os-x-10-9-mavericks/  
- https://github.com/benMcChesney/OF_Kinect_Tutorials  

## Memory
- https://faultlore.com/blah/deinitialize-me-maybe/  
- https://muxup.com/2023q4/storing-data-in-pointers  
- https://www.gingerbill.org/series/memory-allocation-strategies/  

## Multithread
- https://agraphicsguynotes.com/posts/fiber_in_cpp_understanding_the_basics/  
- https://poniesandlight.co.uk/reflect/coroutines_job_system/  

## Reverse engineering
- https://migeel.sk/blog/2023/09/15/reverse-engineering-natively-compiled-dotnet-apps/  

## Security
- https://axleos.com/exploiting-the-iphone-4-part-1-gaining-entry/  
- https://blog.isosceles.com/the-webp-0day/  
- https://www.reversemode.com/2023/10/reversing-france-identite-new-french.html  

## Tutorial
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

# Retro
- http://codetapper.com/amiga/sprite-tricks/  
- https://fms-cat.github.io/thump/  
- https://mitxela.com/projects/console  
- http://skilldrick.github.io/easy6502/#snake  

## Dreamcast
- http://cadcdev.sourceforge.net/softprj/kos/setup.php  
- https://dcemulation.org/?title=Development  
- https://dcemulation.org/phpBB/viewtopic.php?f=29&t=51558  
- https://dcemulation.org/phpBB/viewtopic.php?f=29&t=99166  
- http://dmitry.gr/index.php?r=05.Projects&proj=25.%20VMU%20Hacking  

## Glide
- https://glide.sourceforge.net  
- http://www.gamers.org/dEngine/xf3D/glide/glidepgm.htm  

## Nintendo
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

## Sony
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

## Techno
- https://jcs.org/2025/02/26/imacg4k  

## Vectrex
- https://vandenbran.de/post/2016-02-01-a-modern-toolchain-for-vectrex-development/  
- http://www.gametronik.com/site/emulation/vectrex/  
- https://www.playvectrex.com/designit/chrissalo/toc.htm  

## Video
- http://blog.tynemouthsoftware.co.uk/2023/10/how-the-zx81-generates-video.html  
- https://pcbjunkie.net/index.php/guides/generating-video-with-a-microcontroller/  
- https://www.backoldgaming.com/topic/read/lart-de-la-sync  
- https://www.bigmessowires.com/2023/10/04/classic-macintosh-video-signals-demystified-designing-a-mac-to-vga-adapter-with-lm1881/  

## Books <a id="books"></a>

### Jendrik Illner <a id="jendrik"></a>