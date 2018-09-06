# webgl-info
WebGL features info

Based on [gl-info](https://github.com/Ramshackle-Jamathon/gl-info)

# Usage
```sh
npm install webgl-info
```


```javascript
import WebGLInfo from 'webgl-info';

console.log(WebGLInfo);
```

And you should get a report similar to the following one:
```json
{
    "webgl1": {
        "webglVersion": 1,
        "contextName": "webgl",
        "glVersion": "WebGL 1.0 (OpenGL ES 2.0 Chromium)",
        "vendor": "WebKit",
        "renderer": "WebKit WebGL",
        "unMaskedVendor": "ATI Technologies Inc.",
        "unMaskedRenderer": "AMD Radeon Pro 560 OpenGL Engine",
        "angle": "No",
        "antialias": "Available",
        "majorPerformanceCaveat": "No",
        "bits": {
            "redBits": 8,
            "greenBits": 8,
            "blueBits": 8,
            "alphaBits": 8,
            "depthBits": 24,
            "stencilBits": 8
        },
        "maximum": {
            "maxColorBuffers": 8,
            "maxRenderBufferSize": 16384,
            "maxCombinedTextureImageUnits": 80,
            "maxCubeMapTextureSize": 16384,
            "maxFragmentUniformVectors": 1024,
            "maxTextureImageUnits": 16,
            "maxTextureSize": 16384,
            "maxVaryingVectors": 32,
            "maxVertexAttributes": 16,
            "maxVertexTextureImageUnits": 16,
            "maxVertexUniformVectors": 1024,
            "maxViewportDimensions": [
                16384,
                16384
            ],
            "maxAnisotropy": 16
        },
        "aliasedLineWidthRange": [
            1,
            1
        ],
        "aliasedPointSizeRange": [
            1,
            8191
        ],
        "shaders": {
            "vertexShaderBestPrecision": {
                "high": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "medium": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "low": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "best": "[-2^127, 2^127] (23)"
            },
            "fragmentShaderBestPrecision": {
                "high": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "medium": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "low": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "best": "[-2^127, 2^127] (23)"
            },
            "fragmentShaderFloatIntPrecision": "highp/highp",
            "shadingLanguageVersion": "WebGL GLSL ES 1.0 (OpenGL ES GLSL ES 1.0 Chromium)"
        },
        "extensions": [
            "ANGLE_instanced_arrays",
            "EXT_blend_minmax",
            "EXT_color_buffer_half_float",
            "EXT_frag_depth",
            "EXT_shader_texture_lod",
            "EXT_texture_filter_anisotropic",
            "WEBKIT_EXT_texture_filter_anisotropic",
            "EXT_sRGB",
            "OES_element_index_uint",
            "OES_standard_derivatives",
            "OES_texture_float",
            "OES_texture_float_linear",
            "OES_texture_half_float",
            "OES_texture_half_float_linear",
            "OES_vertex_array_object",
            "WEBGL_color_buffer_float",
            "WEBGL_compressed_texture_s3tc",
            "WEBKIT_WEBGL_compressed_texture_s3tc",
            "WEBGL_compressed_texture_s3tc_srgb",
            "WEBGL_debug_renderer_info",
            "WEBGL_debug_shaders",
            "WEBGL_depth_texture",
            "WEBKIT_WEBGL_depth_texture",
            "WEBGL_draw_buffers",
            "WEBGL_lose_context",
            "WEBKIT_WEBGL_lose_context"
        ]
    },
    "webgl2": {
        "webglVersion": 2,
        "contextName": "webgl2",
        "glVersion": "WebGL 2.0 (OpenGL ES 3.0 Chromium)",
        "vendor": "WebKit",
        "renderer": "WebKit WebGL",
        "unMaskedVendor": "ATI Technologies Inc.",
        "unMaskedRenderer": "AMD Radeon Pro 560 OpenGL Engine",
        "angle": "No",
        "antialias": "Available",
        "majorPerformanceCaveat": "No",
        "bits": {
            "redBits": 8,
            "greenBits": 8,
            "blueBits": 8,
            "alphaBits": 8,
            "depthBits": 24,
            "stencilBits": 8
        },
        "maximum": {
            "maxColorBuffers": 1,
            "maxRenderBufferSize": 16384,
            "maxCombinedTextureImageUnits": 80,
            "maxCubeMapTextureSize": 16384,
            "maxFragmentUniformVectors": 1024,
            "maxTextureImageUnits": 16,
            "maxTextureSize": 16384,
            "maxVaryingVectors": 32,
            "maxVertexAttributes": 16,
            "maxVertexTextureImageUnits": 16,
            "maxVertexUniformVectors": 1024,
            "maxViewportDimensions": [
                16384,
                16384
            ],
            "maxAnisotropy": 16
        },
        "aliasedLineWidthRange": [
            1,
            1
        ],
        "aliasedPointSizeRange": [
            1,
            8191
        ],
        "shaders": {
            "vertexShaderBestPrecision": {
                "high": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "medium": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "low": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "best": "[-2^127, 2^127] (23)"
            },
            "fragmentShaderBestPrecision": {
                "high": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "medium": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "low": "[-1.7014118346046923e+38, 1.7014118346046923e+38] (23 bit mantissa)",
                "best": "[-2^127, 2^127] (23)"
            },
            "fragmentShaderFloatIntPrecision": "highp/highp",
            "shadingLanguageVersion": "WebGL GLSL ES 3.00 (OpenGL ES GLSL ES 3.0 Chromium)"
        },
        "extensions": [
            "EXT_color_buffer_float",
            "EXT_texture_filter_anisotropic",
            "OES_texture_float_linear",
            "WEBGL_compressed_texture_s3tc",
            "WEBGL_compressed_texture_s3tc_srgb",
            "WEBGL_debug_renderer_info",
            "WEBGL_debug_shaders",
            "WEBGL_lose_context"
        ]
    }
}
```
