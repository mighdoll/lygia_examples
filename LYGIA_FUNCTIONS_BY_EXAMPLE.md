# LYGIA Functions Used by Example

This document lists all LYGIA shader library functions used in each example.


## animation_easing
- lygia::animation::easing
- lygia::draw::circle
- lygia::space::ratio
- lygia::space::scale

## animation_sprite
- lygia::animation::spriteLoop
- lygia::sample::nearest
- lygia::space::ratio

## color_brightnessContrast
- lygia::color::brightnessContrast

## color_brightnessContrastMatrix
- lygia::color::brightnessMatrix
- lygia::color::contrastMatrix

## color_daltonize
- lygia::color::daltonize

## color_dither
- lygia::color::dither
- lygia::math::mirror

## color_iridescence_map
- lygia::color::space
- lygia::lighting::iridescence
- lygia::math::const

## color_lut
- lygia::color::lut

## color_mix
- lygia::color::mixOklab
- lygia::color::mixRYB
- lygia::color::mixSpectral
- lygia::color::palette::pigments

## color_mixSpectral_check
- lygia::color::mixSpectral
- lygia::draw::colorChecker
- lygia::math::const
- lygia::space::ratio
- lygia::space::scale

## color_mix_ryb
- lygia::color::mixRYB
- lygia::color::palette::pigments
- lygia::color::palette::pigments::winsor_oil
- lygia::math::saturate

## color_palette_lerp
- lygia::color::mixOklab
- lygia::color::mixRYB
- lygia::color::mixSpectral
- lygia::color::palette::lerp
- lygia::color::palette::pigments
- lygia::color::palette::pigments::gamblin_oil
- lygia::color::palette::pigments::golden_acrylic
- lygia::color::palette::pigments::liquitex_acrylic
- lygia::color::palette::pigments::rembrandt_oil
- lygia::color::palette::pigments::winsor_acrylic
- lygia::color::palette::pigments::winsor_gouache
- lygia::color::palette::pigments::winsor_oil

## color_pigments
- lygia::color::palette::pigments
- lygia::color::palette::pigments::gamblin_oil
- lygia::color::palette::pigments::golden_acrylic
- lygia::color::palette::pigments::liquitex_acrylic
- lygia::color::palette::pigments::rembrandt_oil
- lygia::color::palette::pigments::winsor_acrylic
- lygia::color::palette::pigments::winsor_gouache
- lygia::color::palette::pigments::winsor_oil
- lygia::color::space::rgb2srgb
- lygia::color::space::srgb2rgb
- lygia::draw::stroke

## color_ryb
- lygia::color::hueShiftRYB
- lygia::color::space::hsv2ryb
- lygia::draw::circle
- lygia::math::const
- lygia::math::cubicMix
- lygia::math::decimate

## color_wada
- lygia::color::luma
- lygia::color::palette::wada::value
- lygia::draw::digits

## color_wada_dyads
- lygia::color::luma
- lygia::color::palette::wada::dyad
- lygia::color::palette::wada::value
- lygia::draw::digits

## color_wada_tetrads
- lygia::color::luma
- lygia::color::palette::wada::tetrad
- lygia::color::palette::wada::value
- lygia::draw::digits

## color_wada_triads
- lygia::color::luma
- lygia::color::palette::wada::triad
- lygia::color::palette::wada::value
- lygia::draw::digits

## color_wavelength
- lygia::color::palette::spectral
- lygia::color::space
- lygia::draw::digits
- lygia::math::map

## color_zorn
- lygia::color::mixRYB
- lygia::color::palette::pigments
- lygia::color::palette::pigments::gamblin_oil
- lygia::color::palette::pigments::golden_acrylic
- lygia::color::palette::pigments::liquitex_acrylic
- lygia::color::palette::pigments::rembrandt_oil
- lygia::color::palette::pigments::winsor_acrylic
- lygia::color::palette::pigments::winsor_gouache
- lygia::color::palette::pigments::winsor_oil
- lygia::color::palette::zorn
- lygia::math::saturate

## distort_pincushion
- lygia::distort::pincushion

## draw_aa
- lygia::color::space::linear2gamma
- lygia::math::aafloor
- lygia::math::aafract
- lygia::math::aastep
- lygia::math::const
- lygia::space::cart2polar

## draw_colorChecker
- lygia::color::space::lab2srgb
- lygia::color::space::lch2srgb
- lygia::color::space::xyY2srgb
- lygia::color::space::xyz2srgb
- lygia::draw::colorChecker
- lygia::math::const
- lygia::space::ratio
- lygia::space::rotate
- lygia::space::scale

## draw_debug1
- lygia::color::space::linear2gamma
- lygia::draw::axis
- lygia::draw::matrix
- lygia::draw::point
- lygia::lighting::raymarch
- lygia::math::inverse
- lygia::math::transpose
- lygia::sdf
- lygia::space::perspective
- lygia::space::ratio

## draw_debug2
- lygia::draw::axis
- lygia::draw::colorPicker
- lygia::draw::matrix
- lygia::draw::point
- lygia::lighting::material::new
- lygia::lighting::pbrLittle
- lygia::space::ratio

## draw_digits
- lygia::draw::digits
- lygia::draw::fill
- lygia::draw::stroke
- lygia::sdf::circleSDF

## draw_julia
- lygia::color::palette::fire
- lygia::color::palette::hue
- lygia::color::palette::spectral
- lygia::color::palette::water
- lygia::sdf::juliaSDF

## draw_koch
- lygia::draw::stroke
- lygia::sdf::kochSDF

## draw_mandelbulb
- lygia::color::space::linear2gamma
- lygia::lighting::raymarch
- lygia::sdf::mandelbulbSDF
- lygia::sdf::opUnion
- lygia::space::ratio

## draw_shapes
- lygia::draw::fill
- lygia::sdf::circleSDF
- lygia::sdf::crossSDF
- lygia::sdf::flowerSDF
- lygia::sdf::gearSDF
- lygia::sdf::heartSDF
- lygia::sdf::hexSDF
- lygia::sdf::polySDF
- lygia::sdf::raysSDF
- lygia::sdf::rectSDF
- lygia::sdf::rhombSDF
- lygia::sdf::spiralSDF
- lygia::sdf::starSDF
- lygia::sdf::triSDF
- lygia::sdf::vesicaSDF
- lygia::space::aspect
- lygia::space::center
- lygia::space::ratio
- lygia::space::rotate
- lygia::space::uncenter

## draw_supershape
- lygia::draw::fill
- lygia::sdf::superShapeSDF

## draw_tiles
- lygia::draw::fill
- lygia::sdf::heartSDF
- lygia::space::brickTile
- lygia::space::checkerTile
- lygia::space::hexTile
- lygia::space::mirrorTile
- lygia::space::ratio
- lygia::space::scale
- lygia::space::sqTile
- lygia::space::triTile
- lygia::space::windmillTile

## filter_bilateral2D
- lygia::draw::digits
- lygia::filter::bilateral
- lygia::sample::clamp2edge

## filter_bilinear2D
- lygia::draw::digits
- lygia::filter::bilinear
- lygia::sample::clamp2edge

## filter_boxBlur1D
- lygia::draw::digits
- lygia::filter::boxBlur
- lygia::sample::clamp2edge

## filter_boxBlur2D
- lygia::draw::digits
- lygia::filter::boxBlur
- lygia::sample::clamp2edge

## filter_edge2D
- lygia::draw::digits
- lygia::filter::edge
- lygia::sample::clamp2edge

## filter_fibonacciBokeh
- lygia::draw::digits
- lygia::filter::fibonacciBokeh
- lygia::sample::clamp2edge

## filter_gaussianBlur1D
- lygia::draw::digits
- lygia::filter::gaussianBlur
- lygia::sample::clamp2edge

## filter_gaussianBlur2D
- lygia::draw::digits
- lygia::filter::gaussianBlur
- lygia::sample::clamp2edge

## filter_kuwahara2D
- lygia::draw::digits
- lygia::filter::kuwahara
- lygia::sample::clamp2edge

## filter_laplacian2D
- lygia::draw::digits
- lygia::filter::laplacian
- lygia::sample::clamp2edge

## filter_median2D
- lygia::draw::digits
- lygia::draw::stroke
- lygia::filter::median
- lygia::sample::clamp2edge

## filter_noiseBlur2D
- lygia::draw::digits
- lygia::filter::noiseBlur
- lygia::sample::clamp2edge

## filter_radialBlur2D
- lygia::draw::digits
- lygia::filter::radialBlur
- lygia::sample::clamp2edge

## filter_sharpen2D
- lygia::filter::sharpen

## generative_cnoise
- lygia::generative::cnoise

## generative_curl
- lygia::generative::curl
- lygia::generative::gnoise
- lygia::generative::snoise
- lygia::generative::wavelet
- lygia::math::const

## generative_fbm
- lygia::generative::fbm

## generative_noised
- lygia::generative::noised

## generative_pnoise
- lygia::generative::pnoise

## generative_psrdnoise
- lygia::generative::psrdnoise
- lygia::lighting::material::new
- lygia::lighting::pbrLittle

## generative_random
- lygia::generative::random

## generative_snoise
- lygia::generative::snoise

## generative_voronoi
- lygia::generative::voronoi

## generative_voronoise
- lygia::generative::voronoise

## generative_wavelet
- lygia::generative::wavelet

## generative_worley
- lygia::generative::worley

## lighting_atmosphere
- lygia::color::tonemap
- lygia::lighting::atmosphere
- lygia::space::equirect2xyz
- lygia::space::fisheye2xyz
- lygia::space::ratio

## lighting_gooch
- lygia::color::space::linear2gamma
- lygia::lighting::gooch
- lygia::lighting::material::new

## lighting_normal
- lygia::lighting::material::normal

## lighting_pbr
- lygia::color::space::linear2gamma
- lygia::lighting::material::new
- lygia::lighting::pbr

## lighting_pbrClearCoat
- lygia::color::space::linear2gamma
- lygia::lighting::material::new
- lygia::lighting::pbrClearCoat

## lighting_pbrGlass
- lygia::color::space::linear2gamma
- lygia::lighting::material::new
- lygia::lighting::pbrGlass

## lighting_pbrIridescence
- lygia::color::palette::hue
- lygia::color::space::gamma2linear
- lygia::color::space::linear2gamma
- lygia::generative::fbm
- lygia::lighting::material::new
- lygia::lighting::pbr
- lygia::lighting::pbrClearCoat
- lygia::lighting::pbrGlass
- lygia::math::bump

## lighting_pbrLittle
- lygia::color::space::linear2gamma
- lygia::generative::fbm
- lygia::lighting::material::new
- lygia::lighting::pbrLittle

## lighting_pbrLittle_deferred
- lygia::color::space::linear2gamma
- lygia::generative::random
- lygia::lighting::material::new
- lygia::lighting::pbrLittle
- lygia::lighting::ssao
- lygia::math::inverse
- lygia::sample::viewPosition

## lighting_pbrSsS
- lygia::color::space::linear2gamma
- lygia::draw::stroke
- lygia::generative::fbm
- lygia::lighting::material::new
- lygia::lighting::pbr
- lygia::math::mirror

## lighting_pbr_deferred
- lygia::color::space::linear2gamma
- lygia::generative::random
- lygia::lighting::material::new
- lygia::lighting::pbr
- lygia::lighting::ssao
- lygia::math::inverse
- lygia::sample::viewPosition

## lighting_pbr_dynamic
- lygia::color::space::linear2gamma
- lygia::lighting::atmosphere
- lygia::lighting::material::new
- lygia::lighting::pbr
- lygia::lighting::raymarch::camera
- lygia::sample::zero
- lygia::space::lookAt

## lighting_pbr_lights
- lygia::color::space::linear2gamma
- lygia::lighting::light::point
- lygia::lighting::material::new
- lygia::lighting::pbr

## lighting_position
- lygia::math::inverse
- lygia::sample::viewPosition

## lighting_raymarching
- lygia::color::space::linear2gamma
- lygia::lighting::raymarch
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_gooch
- lygia::color::space::linear2gamma
- lygia::lighting::envMap
- lygia::lighting::gooch
- lygia::lighting::raymarch
- lygia::lighting::raymarch::softShadow
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_pbr
- lygia::color::space::linear2gamma
- lygia::lighting::atmosphere
- lygia::lighting::envMap
- lygia::lighting::pbr
- lygia::lighting::raymarch
- lygia::lighting::raymarch::softShadow
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_pbrClearCoat
- lygia::color::space::linear2gamma
- lygia::lighting::atmosphere
- lygia::lighting::envMap
- lygia::lighting::pbrClearCoat
- lygia::lighting::raymarch
- lygia::lighting::raymarch::softShadow
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_pbrGlass
- lygia::color::space::linear2gamma
- lygia::lighting::atmosphere
- lygia::lighting::envMap
- lygia::lighting::pbrGlass
- lygia::lighting::raymarch
- lygia::lighting::raymarch::softShadow
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_pbrIridescence
- lygia::color::space::linear2gamma
- lygia::generative::fbm
- lygia::lighting::atmosphere
- lygia::lighting::envMap
- lygia::lighting::pbr
- lygia::lighting::raymarch
- lygia::lighting::raymarch::softShadow
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_pbrLittle
- lygia::color::space::linear2gamma
- lygia::lighting::atmosphere
- lygia::lighting::envMap
- lygia::lighting::pbrLittle
- lygia::lighting::raymarch
- lygia::lighting::raymarch::softShadow
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_pbr_volume
- lygia::color::space::linear2gamma
- lygia::generative::fbm
- lygia::lighting::atmosphere
- lygia::lighting::envMap
- lygia::lighting::pbr
- lygia::lighting::raymarch
- lygia::lighting::raymarch::softShadow
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_return
- lygia::color::palette::heatmap
- lygia::color::space::linear2gamma
- lygia::lighting::raymarch
- lygia::math::map
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_spheric
- lygia::color::space::linear2gamma
- lygia::lighting::raymarch
- lygia::sdf
- lygia::space::ratio

## lighting_raymarching_volume
- lygia::color::space::linear2gamma
- lygia::generative::fbm
- lygia::lighting::raymarch
- lygia::sdf
- lygia::space::ratio

## lighting_shadow
- lygia::sample::shadowPCF

## lighting_sphereMap
- lygia::lighting::sphereMap
- lygia::sample::shadowPCF

## lighting_sphericalHarmonics
- lygia::color::tonemap
- lygia::lighting::sphericalHarmonics
- lygia::sample::shadowPCF

## lighting_ssao
- lygia::color::tonemap
- lygia::generative::random
- lygia::lighting::sphericalHarmonics
- lygia::lighting::ssao
- lygia::sample::shadowPCF

## lighting_ssr
- lygia::color::space::linear2gamma
- lygia::lighting::material::new
- lygia::lighting::pbr
- lygia::lighting::ssr
- lygia::lighting::toShininess
- lygia::math::powFast
- lygia::math::saturate

## lighting_volumetric
- lygia::color::space::linear2gamma
- lygia::generative::random
- lygia::lighting::material::new
- lygia::lighting::pbrLittle
- lygia::lighting::volumetricLightScattering
- lygia::math::const

## math_functions
- lygia::color::palette::hue
- lygia::draw::stroke
- lygia::math::bump
- lygia::math::cubic
- lygia::math::decimate
- lygia::math::gain
- lygia::math::gaussian
- lygia::math::invCubic
- lygia::math::invQuartic
- lygia::math::mirror
- lygia::math::parabola
- lygia::math::permute
- lygia::math::quartic
- lygia::math::quintic
- lygia::math::saturate
- lygia::space::ratio
- lygia::space::scale

## math_gaussian
- lygia::draw::stroke
- lygia::math::gaussian

## math_quat
- lygia::color::space::linear2gamma
- lygia::lighting::material::new
- lygia::lighting::pbr

## morphological_alphaFill
- lygia::morphological::alphaFill
- lygia::sample::clamp2edge

## morphological_dilation
- lygia::morphological::dilation

## morphological_erosion
- lygia::morphological::erosion

## morphological_marchinSquares
- lygia::generative::pnoise
- lygia::morphological::marchingSquares
- lygia::space::ratio

## morphological_poissonFill
- lygia::morphological::pyramid::downscale
- lygia::morphological::pyramid::upscale

## sample_3Dsdf
- lygia::color::space::linear2gamma
- lygia::lighting::raymarch
- lygia::math::cubic
- lygia::math::quartic
- lygia::math::quintic
- lygia::math::saturate
- lygia::sample::3DSdf
- lygia::sample::bicubic
- lygia::sample::nearest
- lygia::sample::smooth
- lygia::sdf
- lygia::space::ratio
- lygia::space::scale

## sample_bracketing
- lygia::draw::arrows
- lygia::generative::noised
- lygia::math::const
- lygia::sample::bracketing

## sample_dither
- lygia::color::luma
- lygia::math::decimate
- lygia::sample::dither

## sample_dof
- lygia::lighting::material::new
- lygia::lighting::pbr
- lygia::sample::clamp2edge
- lygia::sample::dof
- lygia::space::linearizeDepth

## sample_equirect
- lygia::color::tonemap
- lygia::generative::srandom
- lygia::lighting::envMap
- lygia::lighting::fresnelReflection
- lygia::lighting::ior::2f0
- lygia::lighting::reflection
- lygia::math::const
- lygia::math::mirror
- lygia::math::saturate
- lygia::sample::equirect
- lygia::space::lookAt

## sample_filter_bicubic
- lygia::sample::bicubic

## sample_filter_nearest
- lygia::sample::nearest

## sample_filter_smooth
- lygia::sample::bicubic
- lygia::sample::nearest
- lygia::sample::smooth

## sample_triplanar
- lygia::sample::triplanar
- lygia::sample::untile

## sample_wrap
- lygia::math::const
- lygia::sample::clamp2edge
- lygia::sample::repeat

## sample_wrap_clamp
- lygia::math::const
- lygia::sample::clamp2edge

## sample_wrap_mirror
- lygia::math::const
- lygia::sample::mirror

## sample_wrap_repeat
- lygia::math::const
- lygia::sample::repeat
- lygia::sample::zero

## sample_wrap_untile
- lygia::math::const
- lygia::sample::untile

## sample_wrap_zero
- lygia::math::const
- lygia::sample::zero
