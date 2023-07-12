project(
  'libdeflate',
  'c',
  meson_version: '>= 0.63.0',
  version : '1.18' ,
  license : 'MIT'
)


libdeflate_dep = declare_dependency(include_directories: '.',
                                    sources: [
                                    'lib/adler32.c',
                                    'lib/crc32.c',
                                    'lib/deflate_compress.c',
                                    'lib/deflate_decompress.c',
                                    'lib/gzip_compress.c',
                                    'lib/gzip_decompress.c',
                                    'lib/utils.c',
                                    'lib/zlib_compress.c',
                                    'lib/zlib_decompress.c',
                                    'lib/arm/cpu_features.c',
                                    'lib/x86/cpu_features.c'
                                    ])
