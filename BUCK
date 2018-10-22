def merge_dicts(x, y): 
  z = x.copy()
  z.update(y)
  return z

prebuilt_cxx_library(
  name = 'ippicv', 
  header_namespace = '', 
  exported_platform_headers = [
    (
      '^macos.*', 
      subdir_glob([
        ('build/macos/3rdparty/ippicv/ippicv_mac/include', '**/*.h'), 
      ])
    ), 
  ], 
  platform_static_lib = [
    ('^macos.*', 'build/macos/3rdparty/ippicv/ippicv_mac/lib/intel64/libippicv.a'), 
  ], 
)

cxx_library(
  name = "build_modules_core_test_precomp_hpp-headers",
  header_namespace = '',
  exported_headers = subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.h"),
    ("modules/highgui/include", "**/*.hpp"), 
  ]),
)

cxx_library(
  name = 'build_modules_ts_precomp_hpp-headers',
  header_namespace = '', 
  exported_headers = subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_mac/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"), 
  ]), 
)

cxx_library(
  name = "build_modules_core_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/core/src", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h")
  ]), {
    
  }),
)

cxx_library(
  name = "build_modules_imgproc_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/imgproc/src", "**/*.hpp"),
    ("modules/imgproc/src", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_imgcodecs_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.h")
  ]), {
    
  }),
)

cxx_library(
  name = "build_modules_videoio_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.h")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_highgui_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.h"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.h")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_core_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = 'build_modules_flann_precomp_hpp-headers', 
  header_namespace = '', 
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/flann/include", "**/*.hpp"),
    ("modules/flann/include", "**/*.h"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"), 
  ]), 
  deps = [
    ':ippicv', 
    ':ippiw', 
  ],
)

cxx_library(
  name = "build_modules_flann_test_precomp_hpp-headers",
  header_namespace = '',
  exported_headers = subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/flann/include", "**/*.hpp"),
    ("modules/flann/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"),
  ]), 
)

cxx_library(
  name = 'build_modules_imgproc_test_precomp_hpp-headers',
  header_namespace = '',
  exported_headers = subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_mac/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/highgui/include", "**/*.hpp"), 
  ]), 
)

cxx_library(
  name = "build_modules_imgproc_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"),
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_ml_precomp_hpp-headers",
  header_namespace = '',
  exported_headers = subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_mac/include", "**/*.h"),
    ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.hpp"),
    ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.h"),
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/ml/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
  ]), 
)

cxx_library(
  name = "build_modules_ml_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/ml/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"),
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_objdetect_test_precomp_hpp-headers",
  header_namespace = '',
  exported_headers = subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/objdetect/include", "**/*.hpp"),
    ("modules/objdetect/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp")
  ]), 
)

cxx_library(
  name = "build_modules_objdetect_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.h"),
("build/macos", "**/*.hpp"),
("modules/objdetect/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_objdetect_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/objdetect/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_photo_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/photo/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_photo_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.h"),
("build/macos", "**/*.hpp"),
("modules/photo/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_photo_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/photo/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_viz_precomp_hpp-headers",
  header_namespace = '',
  exported_headers = subdir_glob([
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/viz/src", "**/*.h"),
    ("modules/viz/src", "**/*.hpp"),
    ("modules/viz/src/vtk", "**/*.h"),
    ("modules/viz/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"), 
  ]), 
)

cxx_library(
  name = "build_modules_viz_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/viz/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"),
    ("modules/viz/test", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_dnn_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/dnn/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"),
    ("modules/dnn/test", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_dnn_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.hpp"),
    ("modules/dnn/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_dnn_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/dnn/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_imgcodecs_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/imgproc/include", "**/*.h"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_imgcodecs_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_videoio_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/videoio/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/imgproc/include", "**/*.h"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_videoio_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/videoio/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_highgui_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/highgui/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_features2d_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/features2d/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp")
  ]), {
    
  }),
)

cxx_library(
  name = "build_modules_features2d_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/features2d/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_features2d_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/features2d/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_calib3d_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.h"),
("build/macos", "**/*.hpp"),
("modules/calib3d/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_calib3d_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/calib3d/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_calib3d_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/calib3d/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_shape_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.h"),
("build/macos", "**/*.hpp"),
("modules/shape/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp"),
("modules/calib3d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_shape_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/shape/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_stitching_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/stitching/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_stitching_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/stitching/src", "**/*.hpp"),
("modules/stitching/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp"),
("modules/calib3d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_stitching_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/stitching/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_video_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.h"),
("build/macos", "**/*.hpp"),
("modules/video/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_video_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/video/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_video_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/video/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_videostab_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.h"),
("build/macos", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp"),
("modules/calib3d/include", "**/*.hpp"),
("modules/video/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_videostab_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/videostab/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/flann/include", "**/*.hpp"),
("modules/flann/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/photo/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp"),
("modules/features2d/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_superres_perf_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/ts/include", "**/*.hpp"),
("modules/ts/include", "**/*.h"),
("modules/superres/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_superres_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippicv_lnx/include", "**/*.h"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"),
("build/macos/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"),
("build/macos", "**/*.hpp"),
("build/macos", "**/*.h"),
("modules/superres/src", "**/*.hpp"),
("modules/superres/include", "**/*.hpp"),
("modules/core/include", "**/*.hpp"),
("modules/core/include", "**/*.h"),
("modules/imgproc/include", "**/*.hpp"),
("modules/videoio/include", "**/*.hpp"),
("modules/video/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_library(
  name = "build_modules_superres_test_precomp_hpp-headers",
  header_namespace= '',
  compiler_flags = [],
  preprocessor_flags = [],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/ts/include", "**/*.h"),
    ("modules/superres/include", "**/*.hpp"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp")
  ]), {
    
  }),
  
  
  srcs = [] + [
    
  ],
  linker_flags = [],
  exported_linker_flags = [],
  deps = [],
  visibility = []
)

cxx_precompiled_header(
  name = "build_modules_core_test_precomp_hpp",
  src = "build/macos/modules/core/test_precomp.hpp",
  deps = [
    ":build_modules_core_test_precomp_hpp-headers", 
  ], 
)

cxx_precompiled_header(
  name = "build_modules_ts_precomp_hpp",
  # src = "build/macos/modules/ts/precomp.hpp",
  src = "modules/ts/src/precomp.hpp",
  deps = [
    ":build_modules_ts_precomp_hpp-headers", 
  ], 
)

cxx_precompiled_header(
    name = "build_modules_core_precomp_hpp",
    src = "build/macos/modules/core/precomp.hpp",
    deps = [":build_modules_core_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_imgproc_precomp_hpp",
    src = "build/macos/modules/imgproc/precomp.hpp",
    deps = [":build_modules_imgproc_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_imgcodecs_precomp_hpp",
    src = "build/macos/modules/imgcodecs/precomp.hpp",
    deps = [":build_modules_imgcodecs_precomp_hpp-headers"]
  )

cxx_precompiled_header(
  name = "build_modules_videoio_precomp_hpp",
  src = "build/macos/modules/videoio/precomp.hpp",
  deps = [
    ":build_modules_videoio_precomp_hpp-headers", 
  ], 
)

cxx_precompiled_header(
    name = "build_modules_highgui_precomp_hpp",
    src = "build/macos/modules/highgui/precomp.hpp",
    deps = [":build_modules_highgui_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_core_perf_precomp_hpp",
    src = "build/macos/modules/core/perf_precomp.hpp",
    deps = [":build_modules_core_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
  name = "build_modules_flann_precomp_hpp",
  # src = "build/macos/modules/flann/precomp.hpp",
  src = "modules/flann/src/precomp.hpp",
  deps = [
    ":build_modules_flann_precomp_hpp-headers", 
  ], 
)

cxx_precompiled_header(
    name = "build_modules_flann_test_precomp_hpp",
    src = "build/macos/modules/flann/test_precomp.hpp",
    deps = [":build_modules_flann_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_imgproc_test_precomp_hpp",
    src = "build/macos/modules/imgproc/test_precomp.hpp",
    deps = [":build_modules_imgproc_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_imgproc_perf_precomp_hpp",
    src = "build/macos/modules/imgproc/perf_precomp.hpp",
    deps = [":build_modules_imgproc_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
  name = "build_modules_ml_precomp_hpp",
  src = "modules/ml/src/precomp.hpp",
  deps = [
    ":build_modules_ml_precomp_hpp-headers", 
  ], 
)

cxx_precompiled_header(
    name = "build_modules_ml_test_precomp_hpp",
    src = "build/macos/modules/ml/test_precomp.hpp",
    deps = [":build_modules_ml_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_objdetect_test_precomp_hpp",
    src = "build/macos/modules/objdetect/test_precomp.hpp",
    deps = [":build_modules_objdetect_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_objdetect_precomp_hpp",
    src = "build/macos/modules/objdetect/precomp.hpp",
    deps = [":build_modules_objdetect_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_objdetect_perf_precomp_hpp",
    src = "build/macos/modules/objdetect/perf_precomp.hpp",
    deps = [":build_modules_objdetect_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_photo_test_precomp_hpp",
    src = "build/macos/modules/photo/test_precomp.hpp",
    deps = [":build_modules_photo_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_photo_precomp_hpp",
    src = "build/macos/modules/photo/precomp.hpp",
    deps = [":build_modules_photo_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_photo_perf_precomp_hpp",
    src = "build/macos/modules/photo/perf_precomp.hpp",
    deps = [":build_modules_photo_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
  name = 'build_modules_viz_precomp_hpp', 
  src = 'modules/viz/src/precomp.hpp', 
  deps = [
    ':build_modules_viz_precomp_hpp-headers', 
  ], 
)

cxx_precompiled_header(
    name = "build_modules_viz_test_precomp_hpp",
    src = "build/macos/modules/viz/test_precomp.hpp",
    deps = [":build_modules_viz_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_dnn_test_precomp_hpp",
    src = "build/macos/modules/dnn/test_precomp.hpp",
    deps = [":build_modules_dnn_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_dnn_precomp_hpp",
    src = "build/macos/modules/dnn/precomp.hpp",
    deps = [":build_modules_dnn_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_dnn_perf_precomp_hpp",
    src = "build/macos/modules/dnn/perf_precomp.hpp",
    deps = [":build_modules_dnn_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_imgcodecs_test_precomp_hpp",
    src = "build/macos/modules/imgcodecs/test_precomp.hpp",
    deps = [":build_modules_imgcodecs_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_imgcodecs_perf_precomp_hpp",
    src = "build/macos/modules/imgcodecs/perf_precomp.hpp",
    deps = [":build_modules_imgcodecs_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_videoio_test_precomp_hpp",
    src = "build/macos/modules/videoio/test_precomp.hpp",
    deps = [":build_modules_videoio_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_videoio_perf_precomp_hpp",
    src = "build/macos/modules/videoio/perf_precomp.hpp",
    deps = [":build_modules_videoio_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_highgui_test_precomp_hpp",
    src = "build/macos/modules/highgui/test_precomp.hpp",
    deps = [":build_modules_highgui_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_features2d_precomp_hpp",
    src = "build/macos/modules/features2d/precomp.hpp",
    deps = [":build_modules_features2d_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_features2d_perf_precomp_hpp",
    src = "build/macos/modules/features2d/perf_precomp.hpp",
    deps = [":build_modules_features2d_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_features2d_test_precomp_hpp",
    src = "build/macos/modules/features2d/test_precomp.hpp",
    deps = [":build_modules_features2d_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_calib3d_precomp_hpp",
    src = "build/macos/modules/calib3d/precomp.hpp",
    deps = [":build_modules_calib3d_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_calib3d_test_precomp_hpp",
    src = "build/macos/modules/calib3d/test_precomp.hpp",
    deps = [":build_modules_calib3d_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_calib3d_perf_precomp_hpp",
    # src = "build/macos/modules/calib3d/perf_precomp.hpp",
    src = "modules/calib3d/perf/perf_precomp.hpp",
    deps = [":build_modules_calib3d_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_shape_precomp_hpp",
    # src = "build/macos/modules/shape/precomp.hpp",
    src = "modules/shape/src/precomp.hpp",
    deps = [":build_modules_shape_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_shape_test_precomp_hpp",
    src = "build/macos/modules/shape/test_precomp.hpp",
    deps = [":build_modules_shape_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_stitching_test_precomp_hpp",
    src = "build/macos/modules/stitching/test_precomp.hpp",
    deps = [":build_modules_stitching_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_stitching_precomp_hpp",
    src = "build/macos/modules/stitching/precomp.hpp",
    deps = [":build_modules_stitching_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_stitching_perf_precomp_hpp",
    src = "build/macos/modules/stitching/perf_precomp.hpp",
    deps = [":build_modules_stitching_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_video_precomp_hpp",
    src = "build/macos/modules/video/precomp.hpp",
    deps = [":build_modules_video_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_video_test_precomp_hpp",
    src = "build/macos/modules/video/test_precomp.hpp",
    deps = [":build_modules_video_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_video_perf_precomp_hpp",
    src = "build/macos/modules/video/perf_precomp.hpp",
    deps = [":build_modules_video_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_videostab_precomp_hpp",
    src = "build/macos/modules/videostab/precomp.hpp",
    deps = [":build_modules_videostab_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_videostab_test_precomp_hpp",
    src = "build/macos/modules/videostab/test_precomp.hpp",
    deps = [":build_modules_videostab_test_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_superres_perf_precomp_hpp",
    src = "build/macos/modules/superres/perf_precomp.hpp",
    deps = [":build_modules_superres_perf_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_superres_precomp_hpp",
    src = "build/macos/modules/superres/precomp.hpp",
    deps = [":build_modules_superres_precomp_hpp-headers"]
  )

cxx_precompiled_header(
    name = "build_modules_superres_test_precomp_hpp",
    src = "build/macos/modules/superres/test_precomp.hpp",
    deps = [":build_modules_superres_test_precomp_hpp-headers"]
  )
cxx_library(
  name = "ittnotify",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("3rdparty/ittnotify/include", "**/*.h")
  ]), {
    
  }),
  headers = merge_dicts(subdir_glob([
    
  ]), {
    
  }),
  
  srcs = 
  [ (file, []) for file in glob(
      ["3rdparty/ittnotify/src/ittnotify/*.c"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread"],
  deps = [],
  visibility = []
)

cxx_library(
  name = 'ippiw',
  header_namespace = '',
  compiler_flags = [
    "-fsigned-char", 
    "-fdiagnostics-show-option", 
    "-fomit-frame-pointer", 
    "-ffunction-sections", 
    "-fdata-sections", 
    "-fvisibility=hidden", 
    "-fPIC", 
    "-msse", 
    "-msse2", 
    "-msse3", 
  ],
  preprocessor_flags = [
    "-DICV_BASE", 
    # "-DIW_build=macos", 
    '-DIW_BUILD=1', 
    "-DNDEBUG", 
  ],
  exported_headers = subdir_glob([
    # ("build/macos", "**/*.h"), 
  ]), 
  exported_platform_headers = [
    (
      '^macos.*', 
      subdir_glob([ 
        ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.hpp"), 
        ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.h"), 
      ])
    ), 
    (
      '^linux.*', 
      subdir_glob([ 
        ("build/linux/3rdparty/ippicv/ippiw_lnx/include", "**/*.hpp"), 
        ("build/linux/3rdparty/ippicv/ippiw_lnx/include", "**/*.h"), 
      ])
    ), 
  ], 
  platform_srcs = [
    ('^macos.*', glob([ 'build/macos/3rdparty/ippicv/ippiw_mac/src/*.c' ])), 
    ('^linux.*', glob([ 'build/linux/3rdparty/ippicv/ippiw_lnx/src/*.c' ])), 
  ],
  exported_linker_flags = [
    "-pthread", 
  ],
  deps = [
    ':ippicv', 
  ], 
)

cxx_library(
  name = "libjasper",
  header_namespace = '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DEXCLUDE_BMP_SUPPORT","-DEXCLUDE_JPG_SUPPORT","-DEXCLUDE_MIF_SUPPORT","-DEXCLUDE_PGX_SUPPORT","-DEXCLUDE_PNM_SUPPORT","-DEXCLUDE_RAS_SUPPORT","-DNDEBUG"],
  exported_headers = subdir_glob([
    ("3rdparty/libjasper", "**/*.h"), 
  ]), 
  srcs = glob([
    "3rdparty/libjasper/*.c", 
  ]), 
  exported_linker_flags = [
    "-pthread"
  ],
)

cxx_library(
  name = 'libprotobuf', 
  header_namespace= '', 
  compiler_flags = [
    "-fsigned-char", 
    "-fdiagnostics-show-option", 
    "-fomit-frame-pointer", 
    "-ffunction-sections", 
    "-fdata-sections", 
    "-fvisibility=hidden", 
    "-fvisibility-inlines-hidden", 
    "-fPIC", 
    "-msse", 
    "-msse2", 
    "-msse3"
  ],
  preprocessor_flags = [
    "-DHAVE_PTHREAD=1", 
    "-DNDEBUG", 
  ],
  exported_headers = subdir_glob([
    ('3rdparty/protobuf/src', '**/*.h'), 
  ]), 
  headers = subdir_glob([
    ('3rdparty/protobuf/src', '**/internal/*.h'), 
  ]), 
  srcs = glob([
    '3rdparty/protobuf/src/google/protobuf/**/*.cc', 
  ], excludes = [ 
    '3rdparty/protobuf/src/google/protobuf/stubs/atomicops_internals_x86_msvc.cc', 
    '3rdparty/protobuf/src/google/protobuf/util/internal/error_listener.cc', 
  ]), 
  exported_linker_flags = [
    '-pthread', 
  ],
)

cxx_library(
  name = 'opencv_ts',
  header_namespace = '',
  compiler_flags = [
    "-fsigned-char", 
    "-fdiagnostics-show-option", 
    "-fomit-frame-pointer", 
    "-ffunction-sections", 
    "-fdata-sections", 
    "-fvisibility=hidden", 
    "-fvisibility-inlines-hidden", 
    "-fPIC", 
    "-msse", 
    "-msse2", 
    "-msse3", 
  ],
  preprocessor_flags = [
    "-D_USE_MATH_DEFINES", 
    "-D__OPENCV_BUILD=1", 
    "-D__STDC_CONSTANT_MACROS", 
    "-D__STDC_FORMAT_MACROS", 
    "-D__STDC_LIMIT_MACROS", 
    "-DNDEBUG", 
  ],
  exported_headers = subdir_glob([
    ("build/macos", "**/*.hpp"),
    ("modules/ts/include", "**/*.hpp"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.h"),
    ("modules/imgcodecs/include", "**/*.hpp"),
    ("modules/videoio/include", "**/*.hpp"),
    ("modules/highgui/include", "**/*.hpp"), 
  ]), 
  headers = subdir_glob([
    ("modules/ts/src", "**/*.hpp"), 
  ]), 
  precompiled_header = ":build_modules_ts_precomp_hpp",
  srcs = glob([
    'modules/ts/src/*.cpp', 
  ]),
  exported_linker_flags = [
    '-pthread', 
  ],
  deps = [
    # ':opencv_core', 
    ':ippicv', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)

cxx_library(
  name = 'opencv_core',
  header_namespace = '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3","-mssse3","-msse4.1","-mpopcnt","-msse4.2","-mavx","-mf16c","-mfma","-mavx2"],
  preprocessor_flags = [
    "-DCVAPI_EXPORTS", 
    "-DOPENCV_WITH_ITT=1", 
    "-D_USE_MATH_DEFINES", 
    "-D__OPENCV_BUILD=1", 
    "-D__STDC_CONSTANT_MACROS", 
    "-D__STDC_FORMAT_MACROS", 
    "-D__STDC_LIMIT_MACROS", 
    "-DNDEBUG", 
  ],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/3rdparty/ippicv/ippiw_mac/include", "**/*.hpp"),
    ("build/macos", "**/*.hpp"),
    ("build/macos", "**/*.h"),
    ("build/macos", "**/*.inc"),
    ("modules/core/include", "**/*.hpp"),
    ("modules/core/include", "**/*.h"),
    ("build/macos/modules/core", "**/*.hpp"),
    ("build/macos/modules/core", "**/*.inc"),
    ("3rdparty/include/opencl/1.2", "**/*.h"), 
  ]), {
    'modules/core/opencl_kernels_core.hpp': ':gen-build-modules-core-opencl_kernels_core-hpp',
    'opencl_kernels_core.hpp': ':gen-build-modules-core-opencl_kernels_core-hpp',
  }),
  headers = subdir_glob([
    # ("build/macos", "**/*.h"),
    # ("build/macos/opencv2", "**/*.hpp"),
    # ("build/macos/opencv2", "**/*.h"),
    ("modules/core/src", "**/*.hpp"), 
  ]), 
  srcs = 
  [ (file, []) for file in glob(
      ["modules/core/src/**/*.cpp","build/macos/modules/core/opencl_kernels_core.cpp"],
      excludes=["modules/core/src/alloc.cpp"]
   )]
  +
  [ (file, ["-DHAVE_MALLOC_H=1","-DHAVE_MEMALIGN=1","-DHAVE_POSIX_MEMALIGN=1"]) for file in glob(
      ["modules/core/src/alloc.cpp"],
      excludes=[]
   )]
  +
  [ (file, ["-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=SSE4_2"]) for file in glob(
      ["build/macos/modules/core/stat.sse4_2.cpp"],
      excludes=[]
   )]
  +
  [ (file, ["-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX"]) for file in glob(
      ["build/macos/modules/core/mathfuncs_core.avx.cpp"],
      excludes=[]
   )]
  +
  [ (file, ["-DCV_CPU_COMPILE_AVX2=1","-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_FMA3=1","-DCV_CPU_COMPILE_FP16=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX2"]) for file in glob(
      ["build/macos/modules/core/mathfuncs_core.avx2.cpp","build/macos/modules/core/stat.avx2.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-core-opencl_kernels_core-cpp', 
  ],
  exported_linker_flags = [ 
    '-pthread', 
    '-ldl', 
    '-lm', 
    '-lrt', 
    '-lz', 
  ],
  deps = [
    ':ippicv', 
    ':ippiw', 
    ':ittnotify', 
  ],
)

cxx_library(
  name = 'opencv_flann', 
  header_namespace = '', 
  compiler_flags = [
    "-fsigned-char", 
    "-fdiagnostics-show-option", 
    "-fomit-frame-pointer", 
    "-ffunction-sections", 
    "-fdata-sections", 
    "-fvisibility=hidden", 
    "-fvisibility-inlines-hidden", 
    "-fPIC", 
    "-msse", 
    "-msse2", 
    "-msse3", 
  ],
  preprocessor_flags = [
    "-DCVAPI_EXPORTS", 
    "-D_USE_MATH_DEFINES", 
    "-D__OPENCV_BUILD=1", 
    "-D__STDC_CONSTANT_MACROS", 
    "-D__STDC_FORMAT_MACROS", 
    "-D__STDC_LIMIT_MACROS", 
    "-DNDEBUG", 
  ],
  exported_headers = subdir_glob([
    ("modules/flann/include", "**/*.hpp"), 
  ]), 
  headers = subdir_glob([
    ("modules/flann/src", "**/*.hpp"), 
  ]), 
  precompiled_header = ':build_modules_flann_precomp_hpp',
  srcs = glob([
    'modules/flann/src/*.cpp', 
  ]),
  exported_linker_flags = [
    "-pthread", 
    "-ldl", 
    "-lm", 
    "-lrt", 
  ],
  deps = [
    ':ippicv', 
    ":ippiw", 
    ":opencv_core", 
  ],
  visibility = [
    'PUBLIC', 
  ], 
)

cxx_library(
  name = 'opencv_viz',
  header_namespace = '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DvtkRenderingContext2D_AUTOINIT=1(vtkRenderingContextOpenGL)","-DvtkRenderingCore_AUTOINIT=3(vtkInteractionStyle,vtkRenderingFreeType,vtkRenderingOpenGL)","-DNDEBUG"],
  exported_headers = subdir_glob([
    ("modules/viz/include", "**/*.hpp")
  ]), 
  headers = subdir_glob([
    ("modules/viz/src", "**/*.hpp")
  ]), 
  precompiled_header = ':build_modules_viz_precomp_hpp',
  srcs = glob([
    'modules/viz/src/**/*.cpp', 
  ]), 
  exported_linker_flags = [
    "-pthread","-ldl","-lm","-lrt","-lz","-ljpeg","-lpng", 
    "-ltiff","-lfreetype","-lgl2ps","-lGLU","-lSM","-lICE", 
    "-lX11","-lXext","-lXt", 
    "-lGL", 
  ], 
  deps = [
    ':ippicv', 
    ':opencv_core', 
    ':ippiw', 
  ],
  visibility = [
    'PUBLIC', 
  ], 
)

cxx_library(
  name = "opencv_ml",
  header_namespace = '',
  compiler_flags = [
    "-fsigned-char", 
    "-fdiagnostics-show-option", 
    "-fomit-frame-pointer", 
    "-ffunction-sections", 
    "-fdata-sections", 
    "-fvisibility=hidden", 
    "-fvisibility-inlines-hidden", 
    "-fPIC", 
    "-msse", 
    "-msse2", 
    "-msse3", 
  ],
  preprocessor_flags = [
    "-DCVAPI_EXPORTS", 
    "-D_USE_MATH_DEFINES", 
    "-D__OPENCV_BUILD=1", 
    "-D__STDC_CONSTANT_MACROS", 
    "-D__STDC_FORMAT_MACROS", 
    "-D__STDC_LIMIT_MACROS", 
    "-DNDEBUG", 
  ],
  exported_headers = merge_dicts(subdir_glob([
    
  ]), {
    
  }),
  headers = subdir_glob([
    ("modules/ml/src", "**/*.hpp"), 
  ]), 
  precompiled_header = ":build_modules_ml_precomp_hpp",
  srcs = glob([
    "modules/ml/src/*.cpp", 
  ]),
  exported_linker_flags = [
    "-pthread", 
    "-ldl", 
    "-lm", 
    "-lrt", 
  ],
  deps = [
    ":ippicv", 
    ":ippiw", 
    ":opencv_core", 
  ],
  visibility = [
    'PUBLIC', 
  ], 
)

cxx_library(
  name = 'opencv_imgproc', 
  header_namespace = '',
  compiler_flags = [
    "-fsigned-char", 
    "-fdiagnostics-show-option", 
    "-fomit-frame-pointer", 
    "-ffunction-sections", 
    "-fdata-sections", 
    "-fvisibility=hidden", 
    "-fvisibility-inlines-hidden", 
    "-fPIC", 
    "-msse", 
    "-msse2", 
    "-msse3", 
    "-mssse3", 
    "-msse4.1", 
    "-mpopcnt", 
    "-msse4.2", 
    "-mavx", 
    "-mf16c", 
    "-mfma", 
    "-mavx2", 
  ],
  preprocessor_flags = [
    "-DCVAPI_EXPORTS", 
    "-D_USE_MATH_DEFINES", 
    "-D__OPENCV_BUILD=1", 
    "-D__STDC_CONSTANT_MACROS", 
    "-D__STDC_FORMAT_MACROS", 
    "-D__STDC_LIMIT_MACROS", 
    "-DNDEBUG", 
  ],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/imgproc/include", "**/*.hpp"),
    ("modules/imgproc/include", "**/*.h"),
    ("build/macos/modules/imgproc", "**/*.hpp")
  ]), {
    'modules/imgproc/opencl_kernels_imgproc.hpp': ':gen-build-modules-imgproc-opencl_kernels_imgproc-hpp',
    'opencl_kernels_imgproc.hpp': ':gen-build-modules-imgproc-opencl_kernels_imgproc-hpp',
  }),
  headers = subdir_glob([
    ("modules/imgproc/src", "**/*.hpp"),
    ("modules/imgproc/src", "**/*.h"), 
  ]), 
  srcs = 
  [ (file, []) for file in glob(
      ["modules/imgproc/src/*.cpp","build/macos/modules/imgproc/opencl_kernels_imgproc.cpp"],
      excludes=["modules/imgproc/src/corner.avx.cpp","modules/imgproc/src/filter.avx2.cpp","modules/imgproc/src/imgwarp.avx2.cpp","modules/imgproc/src/imgwarp.sse4_1.cpp","modules/imgproc/src/resize.avx2.cpp","modules/imgproc/src/resize.sse4_1.cpp","modules/imgproc/src/undistort.avx2.cpp"]
   )]
  +
  [ (file, ["-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=SSE4_1"]) for file in glob(
      ["modules/imgproc/src/imgwarp.sse4_1.cpp","modules/imgproc/src/resize.sse4_1.cpp"],
      excludes=[]
   )]
  +
  [ (file, ["-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX"]) for file in glob(
      ["modules/imgproc/src/corner.avx.cpp","build/macos/modules/imgproc/accum.avx.cpp"],
      excludes=[]
   )]
  +
  [ (file, ["-DCV_CPU_COMPILE_AVX2=1","-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_FMA3=1","-DCV_CPU_COMPILE_FP16=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX2"]) for file in glob(
      ["modules/imgproc/src/filter.avx2.cpp","modules/imgproc/src/imgwarp.avx2.cpp","modules/imgproc/src/resize.avx2.cpp","modules/imgproc/src/undistort.avx2.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-imgproc-opencl_kernels_imgproc-cpp', 
  ],
  exported_linker_flags = [
    "-pthread", 
    "-ldl", 
    "-lm", 
    "-lrt", 
  ],
  deps = [
    ":ippicv", 
    ":ippiw", 
    ":opencv_core", 
  ],
  visibility = [
    'PUBLIC', 
  ], 
)

cxx_library(
  name = "opencv_imgcodecs",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-DHAVE_IMGCODEC_HDR","-DHAVE_IMGCODEC_PFM","-DHAVE_IMGCODEC_PXM","-DHAVE_IMGCODEC_SUNRASTER","-DHAVE_WEBP","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    
  ]), {
    
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/imgcodecs/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_imgcodecs_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/imgcodecs/src/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt","-lz","-ljpeg","-lwebp","-lpng","-ltiff"],
  deps = [":ippicv",":opencv_imgproc",":ippiw",":libjasper",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_objdetect",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3","-mssse3","-msse4.1","-mpopcnt","-msse4.2","-mavx"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/objdetect/include", "**/*.h"),
("modules/objdetect/include", "**/*.hpp"),
("build/macos/modules/objdetect", "**/*.hpp")
  ]), {
    'modules/objdetect/opencl_kernels_objdetect.hpp': ':gen-build-modules-objdetect-opencl_kernels_objdetect-hpp',
'opencl_kernels_objdetect.hpp': ':gen-build-modules-objdetect-opencl_kernels_objdetect-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/objdetect/src", "**/*.hpp")
  ]), {
    
  }),
  
  srcs = 
  [ (file, []) for file in glob(
      ["modules/objdetect/src/*.cpp","build/macos/modules/objdetect/*.cpp"],
      excludes=["modules/objdetect/src/haar.avx.cpp"]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX"]) for file in glob(
      ["modules/objdetect/src/haar.avx.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-objdetect-opencl_kernels_objdetect-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_imgproc",":ippiw",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_videoio",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/videoio/include", "**/*.hpp"),
("modules/videoio/include", "**/*.h")
  ]), {
    
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/videoio/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_videoio_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/videoio/src/videoio_registry.cpp","modules/videoio/src/videoio_c.cpp","modules/videoio/src/cap.cpp","modules/videoio/src/cap_images.cpp","modules/videoio/src/cap_mjpeg_encoder.cpp","modules/videoio/src/cap_mjpeg_decoder.cpp","modules/videoio/src/container_avi.cpp","modules/videoio/src/cap_v4l.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_imgcodecs",":ippiw",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_photo",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/photo/include", "**/*.hpp"),
("modules/photo/include", "**/*.h"),
("build/macos/modules/photo", "**/*.hpp")
  ]), {
    'modules/photo/opencl_kernels_photo.hpp': ':gen-build-modules-photo-opencl_kernels_photo-hpp',
'opencl_kernels_photo.hpp': ':gen-build-modules-photo-opencl_kernels_photo-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/photo/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_photo_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/photo/src/*.cpp","build/macos/modules/photo/*.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-photo-opencl_kernels_photo-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_imgproc",":ippiw",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_highgui",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-DHAVE_WEBP","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    
  ]), {
    
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/highgui/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_highgui_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/highgui/src/window.cpp","modules/highgui/src/roiSelector.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = [],
  exported_linker_flags = ["-L/home/linuxbrew/.linuxbrew/Cellar/glib/2.54.3/lib","-pthread","-ldl","-lm","-lrt","-lgthread-2.0","-lglib-2.0"],
  deps = [":ippicv",":opencv_videoio",":ippiw",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_features2d",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3","-mssse3","-msse4.1","-mpopcnt","-msse4.2","-mf16c","-mfma","-mavx","-mavx2"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/features2d/include", "**/*.hpp"),
("build/macos/modules/features2d", "**/*.hpp"),
("modules/flann/include", "**/*.h")
  ]), {
    'modules/features2d/opencl_kernels_features2d.hpp': ':gen-build-modules-features2d-opencl_kernels_features2d-hpp',
'opencl_kernels_features2d.hpp': ':gen-build-modules-features2d-opencl_kernels_features2d-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/features2d/src", "**/*.hpp"),
("modules/features2d/src", "**/*.h")
  ]), {
    
  }),
  
  srcs = 
  [ (file, []) for file in glob(
      ["modules/features2d/src/**/*.cpp","build/macos/modules/features2d/*.cpp"],
      excludes=["modules/features2d/src/fast.avx2.cpp"]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX2=1","-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_FMA3=1","-DCV_CPU_COMPILE_FP16=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX2"]) for file in glob(
      ["modules/features2d/src/fast.avx2.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-features2d-opencl_kernels_features2d-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_flann",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_dnn",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3","-mssse3","-msse4.1","-mpopcnt","-msse4.2","-mavx","-mf16c","-mfma","-mavx2","-mavx512f","-mavx512cd","-mavx512vl","-mavx512bw","-mavx512dq"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-DCV_OCL4DNN=1","-DHAVE_PROTOBUF=1","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/dnn/include", "**/*.hpp"),
("build/macos/modules/dnn", "**/*.hpp"),
("modules/dnn/misc/caffe", "**/*.h"),
("modules/dnn/misc/tensorflow", "**/*.h")
  ]), {
    'modules/dnn/opencl_kernels_dnn.hpp': ':gen-build-modules-dnn-opencl_kernels_dnn-hpp',
'opencl_kernels_dnn.hpp': ':gen-build-modules-dnn-opencl_kernels_dnn-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/dnn/src", "**/*.hpp"),
("modules/dnn/src", "**/*.h")
  ]), {
    
  }),
  
  srcs = 
  [ (file, []) for file in glob(
      ["modules/dnn/misc/**/*.cc"],
      excludes=[]
   )]
  +

  [ (file, []) for file in glob(
      ["modules/dnn/src/**/*.cpp","build/macos/modules/dnn/*.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX"]) for file in glob(
      ["build/macos/modules/dnn/layers/layers_common.avx.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX2=1","-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_FMA3=1","-DCV_CPU_COMPILE_FP16=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX2"]) for file in glob(
      ["build/macos/modules/dnn/layers/layers_common.avx2.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX2=1","-DCV_CPU_COMPILE_AVX512_SKX=1","-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_AVX_512F=1","-DCV_CPU_COMPILE_FMA3=1","-DCV_CPU_COMPILE_FP16=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX512_SKX"]) for file in glob(
      ["build/macos/modules/dnn/layers/layers_common.avx512_skx.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-dnn-opencl_kernels_dnn-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_imgproc",":ippiw",":libprotobuf",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_calib3d",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/calib3d/include", "**/*.h"),
("build/macos/modules/calib3d", "**/*.hpp")
  ]), {
    'modules/calib3d/opencl_kernels_calib3d.hpp': ':gen-build-modules-calib3d-opencl_kernels_calib3d-hpp',
'opencl_kernels_calib3d.hpp': ':gen-build-modules-calib3d-opencl_kernels_calib3d-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/calib3d/src", "**/*.h"),
("modules/calib3d/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_calib3d_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/calib3d/src/*.cpp","build/macos/modules/calib3d/*.cpp"],
      excludes=["modules/calib3d/src/chessboard.cpp"]
   )]
   + [
    ':gen-build-modules-calib3d-opencl_kernels_calib3d-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_features2d",":ippiw",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_shape",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    
  ]), {
    
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/shape/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_shape_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/shape/src/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_stitching",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/modules/stitching", "**/*.hpp")
  ]), {
    'modules/stitching/opencl_kernels_stitching.hpp': ':gen-build-modules-stitching-opencl_kernels_stitching-hpp',
'opencl_kernels_stitching.hpp': ':gen-build-modules-stitching-opencl_kernels_stitching-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/stitching/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_stitching_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/stitching/src/*.cpp","build/macos/modules/stitching/*.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-stitching-opencl_kernels_stitching-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_video",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/video/include", "**/*.h"),
("build/macos/modules/video", "**/*.hpp"),
("modules/calib3d/include", "**/*.hpp")
  ]), {
    'modules/video/opencl_kernels_video.hpp': ':gen-build-modules-video-opencl_kernels_video-hpp',
'opencl_kernels_video.hpp': ':gen-build-modules-video-opencl_kernels_video-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/video/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_video_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/video/src/*.cpp","build/macos/modules/video/*.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-video-opencl_kernels_video-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_videostab",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("modules/videostab/include", "**/*.hpp"),
("modules/video/include", "**/*.hpp")
  ]), {
    
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/videostab/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_videostab_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/videostab/src/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_photo",":opencv_video",":ippiw",":opencv_calib3d",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_superres",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/modules/superres", "**/*.hpp")
  ]), {
    'modules/superres/opencl_kernels_superres.hpp': ':gen-build-modules-superres-opencl_kernels_superres-hpp',
'opencl_kernels_superres.hpp': ':gen-build-modules-superres-opencl_kernels_superres-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/superres/src", "**/*.hpp")
  ]), {
    
  }),
    precompiled_header = ":build_modules_superres_precomp_hpp",
  srcs = 
  [ (file, []) for file in glob(
      ["modules/superres/src/*.cpp","build/macos/modules/superres/*.cpp"],
      excludes=[]
   )]
   + [
    ':gen-build-modules-superres-opencl_kernels_superres-cpp', 
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_video",":ippiw",":opencv_calib3d",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_library(
  name = "opencv_java400",
  header_namespace= '',
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIC","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCVAPI_EXPORTS","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  exported_headers = merge_dicts(subdir_glob([
    ("build/macos/modules/java_bindings_generator/gen/cpp", "**/*.hpp"),
("modules/ml/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.h"),
("modules/video/include", "**/*.hpp")
  ]), {
    'modules/java_bindings_generator/gen/cpp/opencv_jni.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-opencv_jni-hpp',
'opencv_jni.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-opencv_jni-hpp',
'modules/java_bindings_generator/gen/cpp/core.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-core-inl-hpp',
'core.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-core-inl-hpp',
'modules/java_bindings_generator/gen/cpp/imgproc.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-imgproc-inl-hpp',
'imgproc.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-imgproc-inl-hpp',
'modules/java_bindings_generator/gen/cpp/ml.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-ml-inl-hpp',
'ml.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-ml-inl-hpp',
'modules/java_bindings_generator/gen/cpp/objdetect.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-objdetect-inl-hpp',
'objdetect.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-objdetect-inl-hpp',
'modules/java_bindings_generator/gen/cpp/photo.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-photo-inl-hpp',
'photo.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-photo-inl-hpp',
'modules/java_bindings_generator/gen/cpp/dnn.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-dnn-inl-hpp',
'dnn.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-dnn-inl-hpp',
'modules/java_bindings_generator/gen/cpp/imgcodecs.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-imgcodecs-inl-hpp',
'imgcodecs.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-imgcodecs-inl-hpp',
'modules/java_bindings_generator/gen/cpp/videoio.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-videoio-inl-hpp',
'videoio.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-videoio-inl-hpp',
'modules/java_bindings_generator/gen/cpp/features2d.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-features2d-inl-hpp',
'features2d.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-features2d-inl-hpp',
'modules/java_bindings_generator/gen/cpp/calib3d.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-calib3d-inl-hpp',
'calib3d.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-calib3d-inl-hpp',
'modules/java_bindings_generator/gen/cpp/video.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-video-inl-hpp',
'video.inl.hpp': ':gen-build-modules-java_bindings_generator-gen-cpp-video-inl-hpp',
  }),
  headers = merge_dicts(subdir_glob([
    ("modules/core/misc/java/src/cpp", "**/*.hpp"),
("modules/dnn/misc/java/src/cpp", "**/*.hpp"),
("modules/features2d/misc/java/src/cpp", "**/*.hpp"),
("modules/java/generator/src/cpp", "**/*.h"),
("modules/java/generator/src/cpp", "**/*.hpp")
  ]), {
    
  }),
  
  srcs = 
  [ (file, []) for file in glob(
      ["modules/core/misc/java/src/cpp/*.cpp","modules/dnn/misc/java/src/cpp/*.cpp","modules/features2d/misc/java/src/cpp/*.cpp","modules/java/generator/src/cpp/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = [],
  exported_linker_flags = ["-pthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ml",":opencv_objdetect",":opencv_photo",":opencv_dnn",":opencv_video",":ippiw",":opencv_calib3d",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)
cxx_binary(
  name = "exe-opencv_version",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D__OPENCV_APPS=1","-D__OPENCV_BUILD=1","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["apps/version/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":ippiw",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_annotation",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D__OPENCV_APPS=1","-D__OPENCV_BUILD=1","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/highgui/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["apps/annotation/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":ippiw",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_visualisation",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D__OPENCV_APPS=1","-D__OPENCV_BUILD=1","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/highgui/include", "**/*.hpp"),
("modules/imgcodecs/include", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["apps/visualisation/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":ippiw",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_core",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DOPENCV_WITH_ITT=1","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/core/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/core/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_flann",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/flann/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/flann/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_flann",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_core",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3","-mssse3","-msse4.1","-mpopcnt","-msse4.2","-mf16c","-mavx","-mfma","-mavx2"],
  preprocessor_flags = ["-DOPENCV_WITH_ITT=1","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/ts/include", "**/*.h"),
("modules/core/test", "**/*.hpp"),
("build/macos/modules/core/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/core/test/**/*.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_DISPATCH_MODE=SSE2"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.sse2.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_DISPATCH_MODE=SSE3"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.sse3.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=SSSE3"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.ssse3.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=SSE4_1"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.sse4_1.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=SSE4_2"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.sse4_2.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_FP16=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=FP16"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.fp16.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.avx.cpp"],
      excludes=[]
   )]
  +

  [ (file, ["-DCV_CPU_COMPILE_AVX2=1","-DCV_CPU_COMPILE_AVX=1","-DCV_CPU_COMPILE_FMA3=1","-DCV_CPU_COMPILE_FP16=1","-DCV_CPU_COMPILE_POPCNT=1","-DCV_CPU_COMPILE_SSE4_1=1","-DCV_CPU_COMPILE_SSE4_2=1","-DCV_CPU_COMPILE_SSSE3=1","-DCV_CPU_DISPATCH_MODE=AVX2"]) for file in glob(
      ["build/macos/modules/core/test/test_intrin128.avx2.cpp","build/macos/modules/core/test/test_intrin256.avx2.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_ml",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/ml/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/ml/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_ml",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_objdetect",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/objdetect/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/objdetect/test/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_objdetect",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_objdetect",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/objdetect/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/objdetect/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_objdetect",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_imgproc",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/imgproc/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/imgproc/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_photo",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/photo/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/photo/test/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_photo",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_imgproc",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/imgproc/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/imgproc/test/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_photo",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/photo/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/photo/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_photo",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_viz",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DvtkRenderingContext2D_AUTOINIT=1(vtkRenderingContextOpenGL)","-DvtkRenderingCore_AUTOINIT=3(vtkInteractionStyle,vtkRenderingFreeType,vtkRenderingOpenGL)","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/viz/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/viz/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_viz",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_dnn",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCV_OCL4DNN=1","-DHAVE_PROTOBUF=1","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/dnn/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/dnn/perf/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_dnn",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_imgcodecs",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DHAVE_IMGCODEC_HDR","-DHAVE_IMGCODEC_PFM","-DHAVE_IMGCODEC_PXM","-DHAVE_IMGCODEC_SUNRASTER","-DHAVE_WEBP","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/imgcodecs/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/imgcodecs/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_imgcodecs",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DHAVE_IMGCODEC_HDR","-DHAVE_IMGCODEC_PFM","-DHAVE_IMGCODEC_PXM","-DHAVE_IMGCODEC_SUNRASTER","-DHAVE_WEBP","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/imgcodecs/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/imgcodecs/perf/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_videoio",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/videoio/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/videoio/perf/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_highgui",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DHAVE_WEBP","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/highgui/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/highgui/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-L/home/linuxbrew/.linuxbrew/Cellar/glib/2.54.3/lib","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":opencv_videoio",":ippiw",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_videoio",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/videoio/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/videoio/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_dnn",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-DCV_OCL4DNN=1","-DHAVE_PROTOBUF=1","-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/dnn/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/dnn/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_dnn",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_features2d",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/features2d/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/features2d/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_features2d",":opencv_flann",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_features2d",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/features2d/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/features2d/test/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_features2d",":opencv_flann",":opencv_highgui",":ippiw",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_ca3d",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/calib3d/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/calib3d/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_calib3d",":opencv_features2d",":ippiw",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_traincascade",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D__OPENCV_APPS=1","-D__OPENCV_BUILD=1","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/imgcodecs/include", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["apps/traincascade/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":ippiw",":opencv_objdetect",":opencv_calib3d",":opencv_features2d",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_flann",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_createsamples",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D__OPENCV_APPS=1","-D__OPENCV_BUILD=1","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/imgcodecs/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp"),
("modules/calib3d/include", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["apps/createsamples/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":ippiw",":opencv_objdetect",":opencv_calib3d",":opencv_features2d",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_flann",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_ca3d",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/calib3d/include", "**/*.hpp"),
("modules/calib3d/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/calib3d/test/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_calib3d",":opencv_features2d",":ippiw",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_shape",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/shape/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/shape/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_shape",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_interactive-caration",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D__OPENCV_APPS=1","-D__OPENCV_BUILD=1","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/imgcodecs/include", "**/*.hpp"),
("modules/highgui/include", "**/*.hpp"),
("modules/calib3d/include", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["apps/interactive-calibration/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":ippiw",":opencv_calib3d",":opencv_features2d",":opencv_highgui",":opencv_videoio",":opencv_flann",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_stitching",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/stitching/include", "**/*.hpp"),
("modules/stitching/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/stitching/test/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_stitching",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_video",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/video/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/video/test/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_video",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_stitching",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/stitching/include", "**/*.hpp"),
("modules/stitching/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/stitching/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_stitching",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_video",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/video/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/video/perf/**/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_video",":opencv_calib3d",":ippiw",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_videostab",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/videostab/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/videostab/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_videostab",":opencv_photo",":opencv_video",":ippiw",":opencv_calib3d",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_test_superres",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__OPENCV_TESTS=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/superres/test", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/superres/test/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_superres",":opencv_video",":ippiw",":opencv_calib3d",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)

cxx_binary(
  name = "exe-opencv_perf_superres",
  compiler_flags = ["-fsigned-char","-fdiagnostics-show-option","-fomit-frame-pointer","-ffunction-sections","-fdata-sections","-fvisibility=hidden","-fvisibility-inlines-hidden","-fPIE","-msse","-msse2","-msse3"],
  preprocessor_flags = ["-D_USE_MATH_DEFINES","-D__OPENCV_BUILD=1","-D__STDC_CONSTANT_MACROS","-D__STDC_FORMAT_MACROS","-D__STDC_LIMIT_MACROS","-DNDEBUG"],
  headers = merge_dicts(subdir_glob([
    ("modules/superres/perf", "**/*.hpp")
  ]), {
    
  }),
  srcs = 
  [ (file, []) for file in glob(
      ["modules/superres/perf/*.cpp"],
      excludes=[]
   )]
   + [
    
  ],
  linker_flags = ["-Wl,--gc-sections","-lpthread","-ldl","-lm","-lrt"],
  deps = [":ippicv",":opencv_ts",":opencv_superres",":opencv_video",":ippiw",":opencv_calib3d",":opencv_features2d",":opencv_flann",":opencv_highgui",":opencv_videoio",":opencv_imgcodecs",":opencv_imgproc",":opencv_core"],
  visibility = []
)
genrule(
    name = 'gen-build-modules-core-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/core/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/core/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/core/$OUT', 
  )

genrule(
    name = 'gen-e04a3d040f07031b1d805a2bea3c425158cdba6b', 
    out = 'out', 
    srcs = glob(["./*.7","modules/java/generator/*.py","modules/java/generator/templates/*.(prolog|template)","modules/python/src2/*.(py|pyc)","build/macos/modules/java_bindings_generator/*.json","build/macos/configured/modules/java/generator/src/java/org/opencv/osgi/*.java","modules/java/generator/src/java/org/opencv/osgi/*.java","modules/java/generator/src/java/org/opencv/utils/*.java","modules/java/generator/android/java/org/opencv/android/*.java","build/macos/configured/modules/java/generator/android/java/org/opencv/android/*.java","modules/java/generator/android/java/org/opencv/engine/*.aidl","modules/java/generator/android-21/java/org/opencv/android/*.java","modules/core/misc/java/*.json","build/macos/configured/modules/core/misc/java/src/java/*.jcode","modules/core/misc/java/src/java/*.java","modules/core/misc/java/test/*.java","modules/core/include/opencv2/core/*.hpp","modules/core/include/opencv2/*.hpp","modules/core/misc/java/src/cpp/*.hpp","modules/imgproc/misc/java/*.json","modules/imgproc/misc/java/src/java/*.java","modules/imgproc/misc/java/test/*.java","modules/imgproc/include/opencv2/imgproc/*.(h|hpp)","modules/imgproc/include/opencv2/imgproc/hal/*.(h|hpp)","modules/imgproc/include/opencv2/*.hpp","modules/imgproc/include/opencv2/imgproc/detail/*.hpp","modules/ml/misc/java/test/*.java","modules/ml/include/opencv2/*.hpp","modules/ml/include/opencv2/ml/*.hpp","modules/objdetect/misc/java/test/*.java","modules/objdetect/include/opencv2/objdetect/*.(h|hpp)","modules/objdetect/include/opencv2/*.hpp","modules/photo/misc/java/test/*.java","modules/photo/include/opencv2/photo/*.(h|hpp)","modules/photo/include/opencv2/*.hpp","modules/dnn/misc/java/*.json","modules/dnn/misc/java/test/*.java","modules/dnn/include/opencv2/*.hpp","modules/dnn/include/opencv2/dnn/*.hpp","modules/imgcodecs/misc/java/test/*.java","modules/imgcodecs/include/opencv2/imgcodecs/*.(h|hpp)","modules/imgcodecs/include/opencv2/*.hpp","modules/videoio/misc/java/test/*.java","modules/videoio/include/opencv2/videoio/*.(h|hpp)","modules/videoio/include/opencv2/*.hpp","modules/highgui/misc/java/*","modules/highgui/misc/java/src/java/*.java","modules/features2d/misc/java/*.json","modules/features2d/misc/java/test/*.java","modules/features2d/include/opencv2/*.hpp","modules/calib3d/misc/java/*.json","modules/calib3d/misc/java/test/*.java","modules/calib3d/include/opencv2/calib3d/*.(h|hpp)","modules/calib3d/include/opencv2/*.hpp","modules/video/misc/java/*.json","modules/video/misc/java/test/*.java","modules/video/include/opencv2/video/*.(h|hpp)","modules/video/include/opencv2/*.hpp"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/java_bindings_generator && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/utils && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/engine && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/cpp && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/ml && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/photo && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgcodecs && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgcodecs && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/videoio && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video && mkdir -p $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/java_bindings_generator && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/utils && mkdir -p build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android && mkdir -p build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/engine && mkdir -p build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/core && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core && mkdir -p build/macos/modules/java_bindings_generator/gen/cpp && mkdir -p build/macos/modules/java_bindings_generator/gen && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/ml && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/photo && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgcodecs && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgcodecs && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/videoio && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d && mkdir -p build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video && mkdir -p build/macos/modules/java_bindings_generator/gen/java/org/opencv/video && python2.7 modules/java/generator/gen_java.py -p modules/python/src2/gen2.py -c build/macos/modules/java_bindings_generator/gen_java.json && cp $TMP/build/macos/modules/java_bindings_generator/gen_java.log $OUT/build/macos/modules/java_bindings_generator/gen_java.log && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi/OpenCVNativeLoader.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi/OpenCVNativeLoader.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi/OpenCVInterface.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi/OpenCVInterface.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/utils/Converters.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/utils/Converters.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/BaseLoaderCallback.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/BaseLoaderCallback.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/StaticHelper.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/StaticHelper.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/InstallCallbackInterface.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/InstallCallbackInterface.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/FpsMeter.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/FpsMeter.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/AsyncServiceHelper.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/AsyncServiceHelper.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/LoaderCallbackInterface.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/LoaderCallbackInterface.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/OpenCVLoader.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/OpenCVLoader.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/CameraBridgeViewBase.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/CameraBridgeViewBase.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/JavaCameraView.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/JavaCameraView.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/Utils.java $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/Utils.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/engine/OpenCVEngineInterface.aidl $OUT/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/engine/OpenCVEngineInterface.aidl && cp $TMP/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraGLSurfaceView.java $OUT/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraGLSurfaceView.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraGLRendererBase.java $OUT/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraGLRendererBase.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/Camera2Renderer.java $OUT/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/Camera2Renderer.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/JavaCamera2View.java $OUT/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/JavaCamera2View.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraRenderer.java $OUT/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraRenderer.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Range.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Range.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/CvException.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/CvException.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfKeyPoint.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfKeyPoint.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRect2d.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRect2d.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Point.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Point.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Rect.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Rect.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat4.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat4.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfByte.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfByte.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat6.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat6.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/TermCriteria.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/TermCriteria.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRotatedRect.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRotatedRect.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Rect2d.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Rect2d.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint2f.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint2f.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRect.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRect.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/KeyPoint.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/KeyPoint.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Point3.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Point3.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint3f.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint3f.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint3.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint3.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Scalar.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Scalar.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfDMatch.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfDMatch.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/RotatedRect.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/RotatedRect.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/DMatch.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/DMatch.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Mat.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Mat.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfInt.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfInt.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Size.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Size.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfInt4.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfInt4.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/CvType.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/CvType.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfDouble.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfDouble.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/SizeTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/SizeTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RectTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RectTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/DMatchTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/DMatchTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/MatTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/MatTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/Point3Test.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/Point3Test.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/MatOfByteTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/MatOfByteTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RangeTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RangeTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/CvTypeTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/CvTypeTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RotatedRectTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RotatedRectTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/CoreTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/CoreTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/KeyPointTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/KeyPointTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/PointTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/PointTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/ScalarTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/ScalarTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/TermCriteriaTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/TermCriteriaTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Core.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Core.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Algorithm.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Algorithm.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/TickMeter.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/TickMeter.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/core.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/core.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/core.txt $OUT/build/macos/modules/java_bindings_generator/gen/core.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Moments.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Moments.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/MomentsTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/MomentsTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/ImgprocTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/ImgprocTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/Subdiv2DTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/Subdiv2DTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Imgproc.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Imgproc.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/CLAHE.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/CLAHE.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Subdiv2D.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Subdiv2D.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHoughBallard.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHoughBallard.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHough.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHough.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHoughGuil.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHoughGuil.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/LineSegmentDetector.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/LineSegmentDetector.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/imgproc.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/imgproc.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/imgproc.txt $OUT/build/macos/modules/java_bindings_generator/gen/imgproc.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/ml/MLTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/ml/MLTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/EM.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/EM.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/SVM.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/SVM.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/Ml.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/Ml.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/NormalBayesClassifier.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/NormalBayesClassifier.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/TrainData.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/TrainData.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/Boost.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/Boost.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/LogisticRegression.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/LogisticRegression.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/ParamGrid.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/ParamGrid.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/KNearest.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/KNearest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/SVMSGD.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/SVMSGD.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/DTrees.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/DTrees.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/ANN_MLP.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/ANN_MLP.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/StatModel.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/StatModel.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/RTrees.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/RTrees.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/ml.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/ml.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/ml.txt $OUT/build/macos/modules/java_bindings_generator/gen/ml.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/ObjdetectTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/ObjdetectTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/HOGDescriptorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/HOGDescriptorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/CascadeClassifierTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/CascadeClassifierTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/CascadeClassifier.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/CascadeClassifier.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/BaseCascadeClassifier.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/BaseCascadeClassifier.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/HOGDescriptor.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/HOGDescriptor.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/Objdetect.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/Objdetect.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/objdetect.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/objdetect.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/objdetect.txt $OUT/build/macos/modules/java_bindings_generator/gen/objdetect.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/photo/PhotoTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/photo/PhotoTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateRobertson.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateRobertson.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapMantiuk.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapMantiuk.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapDurand.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapDurand.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateDebevec.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateDebevec.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapReinhard.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapReinhard.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/Photo.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/Photo.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/AlignExposures.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/AlignExposures.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateCRF.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateCRF.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapDrago.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapDrago.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/AlignMTB.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/AlignMTB.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeDebevec.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeDebevec.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeMertens.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeMertens.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeExposures.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeExposures.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeRobertson.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeRobertson.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/Tonemap.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/Tonemap.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/photo.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/photo.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/photo.txt $OUT/build/macos/modules/java_bindings_generator/gen/photo.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn/DnnListRegressionTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn/DnnListRegressionTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn/DnnTensorFlowTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn/DnnTensorFlowTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Layer.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Layer.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/DictValue.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/DictValue.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Dnn.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Dnn.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Net.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Net.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/dnn.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/dnn.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/dnn.txt $OUT/build/macos/modules/java_bindings_generator/gen/dnn.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgcodecs/ImgcodecsTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgcodecs/ImgcodecsTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgcodecs/Imgcodecs.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgcodecs/Imgcodecs.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/imgcodecs.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/imgcodecs.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/imgcodecs.txt $OUT/build/macos/modules/java_bindings_generator/gen/imgcodecs.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/videoio/VideoCaptureTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/videoio/VideoCaptureTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/VideoWriter.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/VideoWriter.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/Videoio.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/Videoio.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/VideoCapture.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/VideoCapture.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/videoio.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/videoio.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/videoio.txt $OUT/build/macos/modules/java_bindings_generator/gen/videoio.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui/ImageWindow.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui/ImageWindow.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui/HighGui.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui/HighGui.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIFTFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIFTFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/MSERFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/MSERFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SURFFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SURFFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceSL2DescriptorMatcherTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceSL2DescriptorMatcherTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/ORBFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/ORBFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceDescriptorMatcherTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceDescriptorMatcherTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceHammingLUTDescriptorMatcherTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceHammingLUTDescriptorMatcherTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIMPLEBLOBFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIMPLEBLOBFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/FASTFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/FASTFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/DENSEFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/DENSEFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIFTDescriptorExtractorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIFTDescriptorExtractorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/GFTTFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/GFTTFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceL1DescriptorMatcherTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceL1DescriptorMatcherTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BRIEFDescriptorExtractorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BRIEFDescriptorExtractorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/ORBDescriptorExtractorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/ORBDescriptorExtractorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/STARFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/STARFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/Features2dTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/Features2dTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceHammingDescriptorMatcherTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceHammingDescriptorMatcherTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SURFDescriptorExtractorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SURFDescriptorExtractorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/FlannBasedDescriptorMatcherTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/FlannBasedDescriptorMatcherTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/HARRISFeatureDetectorTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/HARRISFeatureDetectorTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWImgDescriptorExtractor.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWImgDescriptorExtractor.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/FastFeatureDetector.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/FastFeatureDetector.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Feature2D.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Feature2D.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BRISK.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BRISK.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BFMatcher.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BFMatcher.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/AgastFeatureDetector.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/AgastFeatureDetector.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/GFTTDetector.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/GFTTDetector.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/DescriptorMatcher.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/DescriptorMatcher.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/KAZE.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/KAZE.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Features2d.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Features2d.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/AKAZE.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/AKAZE.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Params.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Params.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWTrainer.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWTrainer.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/ORB.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/ORB.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/MSER.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/MSER.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWKMeansTrainer.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWKMeansTrainer.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/FlannBasedMatcher.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/FlannBasedMatcher.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/features2d.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/features2d.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/features2d.txt $OUT/build/macos/modules/java_bindings_generator/gen/features2d.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/StereoBMTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/StereoBMTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/StereoSGBMTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/StereoSGBMTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/Calib3dTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/Calib3dTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoSGBM.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoSGBM.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoBM.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoBM.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoMatcher.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoMatcher.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/Calib3d.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/Calib3d.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/calib3d.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/calib3d.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/calib3d.txt $OUT/build/macos/modules/java_bindings_generator/gen/calib3d.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/BackgroundSubtractorMOGTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/BackgroundSubtractorMOGTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/VideoTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/VideoTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/KalmanFilterTest.java $OUT/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/KalmanFilterTest.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/DualTVL1OpticalFlow.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/DualTVL1OpticalFlow.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractorMOG2.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractorMOG2.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/FarnebackOpticalFlow.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/FarnebackOpticalFlow.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/SparseOpticalFlow.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/SparseOpticalFlow.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/DenseOpticalFlow.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/DenseOpticalFlow.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractor.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractor.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/Video.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/Video.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/KalmanFilter.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/KalmanFilter.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/SparsePyrLKOpticalFlow.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/SparsePyrLKOpticalFlow.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractorKNN.java $OUT/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractorKNN.java && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/video.inl.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/video.inl.hpp && cp $TMP/build/macos/modules/java_bindings_generator/gen/video.txt $OUT/build/macos/modules/java_bindings_generator/gen/video.txt && cp $TMP/build/macos/modules/java_bindings_generator/gen/cpp/opencv_jni.hpp $OUT/build/macos/modules/java_bindings_generator/gen/cpp/opencv_jni.hpp', 
  )
genrule(
    name = 'gen-build-modules-java_bindings_generator-gen_java-log', 
    out = 'gen_java.log', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen_java.log $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-osgi-OpenCVNativeLoader-java', 
    out = 'OpenCVNativeLoader.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi/OpenCVNativeLoader.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-osgi-OpenCVInterface-java', 
    out = 'OpenCVInterface.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/osgi/OpenCVInterface.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-utils-Converters-java', 
    out = 'Converters.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/utils/Converters.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-BaseLoaderCallback-java', 
    out = 'BaseLoaderCallback.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/BaseLoaderCallback.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-StaticHelper-java', 
    out = 'StaticHelper.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/StaticHelper.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-InstallCallbackInterface-java', 
    out = 'InstallCallbackInterface.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/InstallCallbackInterface.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-FpsMeter-java', 
    out = 'FpsMeter.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/FpsMeter.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-AsyncServiceHelper-java', 
    out = 'AsyncServiceHelper.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/AsyncServiceHelper.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-LoaderCallbackInterface-java', 
    out = 'LoaderCallbackInterface.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/LoaderCallbackInterface.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-OpenCVLoader-java', 
    out = 'OpenCVLoader.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/OpenCVLoader.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-CameraBridgeViewBase-java', 
    out = 'CameraBridgeViewBase.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/CameraBridgeViewBase.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-JavaCameraView-java', 
    out = 'JavaCameraView.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/JavaCameraView.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-android-Utils-java', 
    out = 'Utils.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/android/Utils.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-java-org-opencv-engine-OpenCVEngineInterface-aidl', 
    out = 'OpenCVEngineInterface.aidl', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android/java/org/opencv/engine/OpenCVEngineInterface.aidl $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-21-java-org-opencv-android-CameraGLSurfaceView-java', 
    out = 'CameraGLSurfaceView.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraGLSurfaceView.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-21-java-org-opencv-android-CameraGLRendererBase-java', 
    out = 'CameraGLRendererBase.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraGLRendererBase.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-21-java-org-opencv-android-Camera2Renderer-java', 
    out = 'Camera2Renderer.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/Camera2Renderer.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-21-java-org-opencv-android-JavaCamera2View-java', 
    out = 'JavaCamera2View.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/JavaCamera2View.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-android-21-java-org-opencv-android-CameraRenderer-java', 
    out = 'CameraRenderer.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/android-21/java/org/opencv/android/CameraRenderer.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Range-java', 
    out = 'Range.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Range.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-CvException-java', 
    out = 'CvException.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/CvException.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfKeyPoint-java', 
    out = 'MatOfKeyPoint.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfKeyPoint.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfRect2d-java', 
    out = 'MatOfRect2d.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRect2d.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Point-java', 
    out = 'Point.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Point.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Rect-java', 
    out = 'Rect.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Rect.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfFloat4-java', 
    out = 'MatOfFloat4.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat4.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfByte-java', 
    out = 'MatOfByte.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfByte.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfFloat6-java', 
    out = 'MatOfFloat6.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat6.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-TermCriteria-java', 
    out = 'TermCriteria.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/TermCriteria.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfRotatedRect-java', 
    out = 'MatOfRotatedRect.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRotatedRect.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Rect2d-java', 
    out = 'Rect2d.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Rect2d.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfPoint2f-java', 
    out = 'MatOfPoint2f.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint2f.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfPoint-java', 
    out = 'MatOfPoint.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfRect-java', 
    out = 'MatOfRect.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfRect.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-KeyPoint-java', 
    out = 'KeyPoint.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/KeyPoint.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Point3-java', 
    out = 'Point3.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Point3.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfPoint3f-java', 
    out = 'MatOfPoint3f.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint3f.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfPoint3-java', 
    out = 'MatOfPoint3.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfPoint3.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Scalar-java', 
    out = 'Scalar.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Scalar.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfFloat-java', 
    out = 'MatOfFloat.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfFloat.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfDMatch-java', 
    out = 'MatOfDMatch.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfDMatch.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-RotatedRect-java', 
    out = 'RotatedRect.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/RotatedRect.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-DMatch-java', 
    out = 'DMatch.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/DMatch.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Mat-java', 
    out = 'Mat.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Mat.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfInt-java', 
    out = 'MatOfInt.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfInt.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Size-java', 
    out = 'Size.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Size.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfInt4-java', 
    out = 'MatOfInt4.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfInt4.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-CvType-java', 
    out = 'CvType.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/CvType.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-MatOfDouble-java', 
    out = 'MatOfDouble.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/MatOfDouble.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-SizeTest-java', 
    out = 'SizeTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/SizeTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-RectTest-java', 
    out = 'RectTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RectTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-DMatchTest-java', 
    out = 'DMatchTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/DMatchTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-MatTest-java', 
    out = 'MatTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/MatTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-Point3Test-java', 
    out = 'Point3Test.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/Point3Test.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-MatOfByteTest-java', 
    out = 'MatOfByteTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/MatOfByteTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-RangeTest-java', 
    out = 'RangeTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RangeTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-CvTypeTest-java', 
    out = 'CvTypeTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/CvTypeTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-RotatedRectTest-java', 
    out = 'RotatedRectTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/RotatedRectTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-CoreTest-java', 
    out = 'CoreTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/CoreTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-KeyPointTest-java', 
    out = 'KeyPointTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/KeyPointTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-PointTest-java', 
    out = 'PointTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/PointTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-ScalarTest-java', 
    out = 'ScalarTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/ScalarTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-core-TermCriteriaTest-java', 
    out = 'TermCriteriaTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/core/TermCriteriaTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Core-java', 
    out = 'Core.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Core.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-Algorithm-java', 
    out = 'Algorithm.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/Algorithm.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-core-TickMeter-java', 
    out = 'TickMeter.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/core/TickMeter.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-core-inl-hpp', 
    out = 'core.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/core.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-core-txt', 
    out = 'core.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/core.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-Moments-java', 
    out = 'Moments.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Moments.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-imgproc-MomentsTest-java', 
    out = 'MomentsTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/MomentsTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-imgproc-ImgprocTest-java', 
    out = 'ImgprocTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/ImgprocTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-imgproc-Subdiv2DTest-java', 
    out = 'Subdiv2DTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgproc/Subdiv2DTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-Imgproc-java', 
    out = 'Imgproc.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Imgproc.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-CLAHE-java', 
    out = 'CLAHE.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/CLAHE.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-Subdiv2D-java', 
    out = 'Subdiv2D.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/Subdiv2D.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-GeneralizedHoughBallard-java', 
    out = 'GeneralizedHoughBallard.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHoughBallard.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-GeneralizedHough-java', 
    out = 'GeneralizedHough.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHough.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-GeneralizedHoughGuil-java', 
    out = 'GeneralizedHoughGuil.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/GeneralizedHoughGuil.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgproc-LineSegmentDetector-java', 
    out = 'LineSegmentDetector.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgproc/LineSegmentDetector.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-imgproc-inl-hpp', 
    out = 'imgproc.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/imgproc.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-imgproc-txt', 
    out = 'imgproc.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/imgproc.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-ml-MLTest-java', 
    out = 'MLTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/ml/MLTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-EM-java', 
    out = 'EM.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/EM.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-SVM-java', 
    out = 'SVM.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/SVM.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-Ml-java', 
    out = 'Ml.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/Ml.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-NormalBayesClassifier-java', 
    out = 'NormalBayesClassifier.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/NormalBayesClassifier.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-TrainData-java', 
    out = 'TrainData.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/TrainData.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-Boost-java', 
    out = 'Boost.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/Boost.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-LogisticRegression-java', 
    out = 'LogisticRegression.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/LogisticRegression.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-ParamGrid-java', 
    out = 'ParamGrid.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/ParamGrid.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-KNearest-java', 
    out = 'KNearest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/KNearest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-SVMSGD-java', 
    out = 'SVMSGD.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/SVMSGD.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-DTrees-java', 
    out = 'DTrees.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/DTrees.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-ANN_MLP-java', 
    out = 'ANN_MLP.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/ANN_MLP.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-StatModel-java', 
    out = 'StatModel.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/StatModel.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-ml-RTrees-java', 
    out = 'RTrees.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/ml/RTrees.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-ml-inl-hpp', 
    out = 'ml.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/ml.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-ml-txt', 
    out = 'ml.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/ml.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-objdetect-ObjdetectTest-java', 
    out = 'ObjdetectTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/ObjdetectTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-objdetect-HOGDescriptorTest-java', 
    out = 'HOGDescriptorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/HOGDescriptorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-objdetect-CascadeClassifierTest-java', 
    out = 'CascadeClassifierTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/objdetect/CascadeClassifierTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-objdetect-CascadeClassifier-java', 
    out = 'CascadeClassifier.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/CascadeClassifier.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-objdetect-BaseCascadeClassifier-java', 
    out = 'BaseCascadeClassifier.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/BaseCascadeClassifier.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-objdetect-HOGDescriptor-java', 
    out = 'HOGDescriptor.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/HOGDescriptor.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-objdetect-Objdetect-java', 
    out = 'Objdetect.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/objdetect/Objdetect.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-objdetect-inl-hpp', 
    out = 'objdetect.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/objdetect.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-objdetect-txt', 
    out = 'objdetect.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/objdetect.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-photo-PhotoTest-java', 
    out = 'PhotoTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/photo/PhotoTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-CalibrateRobertson-java', 
    out = 'CalibrateRobertson.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateRobertson.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-TonemapMantiuk-java', 
    out = 'TonemapMantiuk.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapMantiuk.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-TonemapDurand-java', 
    out = 'TonemapDurand.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapDurand.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-CalibrateDebevec-java', 
    out = 'CalibrateDebevec.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateDebevec.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-TonemapReinhard-java', 
    out = 'TonemapReinhard.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapReinhard.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-Photo-java', 
    out = 'Photo.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/Photo.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-AlignExposures-java', 
    out = 'AlignExposures.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/AlignExposures.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-CalibrateCRF-java', 
    out = 'CalibrateCRF.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/CalibrateCRF.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-TonemapDrago-java', 
    out = 'TonemapDrago.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/TonemapDrago.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-AlignMTB-java', 
    out = 'AlignMTB.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/AlignMTB.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-MergeDebevec-java', 
    out = 'MergeDebevec.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeDebevec.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-MergeMertens-java', 
    out = 'MergeMertens.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeMertens.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-MergeExposures-java', 
    out = 'MergeExposures.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeExposures.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-MergeRobertson-java', 
    out = 'MergeRobertson.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/MergeRobertson.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-photo-Tonemap-java', 
    out = 'Tonemap.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/photo/Tonemap.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-photo-inl-hpp', 
    out = 'photo.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/photo.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-photo-txt', 
    out = 'photo.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/photo.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-dnn-DnnListRegressionTest-java', 
    out = 'DnnListRegressionTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn/DnnListRegressionTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-dnn-DnnTensorFlowTest-java', 
    out = 'DnnTensorFlowTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/dnn/DnnTensorFlowTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-dnn-Layer-java', 
    out = 'Layer.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Layer.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-dnn-DictValue-java', 
    out = 'DictValue.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/DictValue.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-dnn-Dnn-java', 
    out = 'Dnn.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Dnn.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-dnn-Net-java', 
    out = 'Net.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/dnn/Net.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-dnn-inl-hpp', 
    out = 'dnn.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/dnn.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-dnn-txt', 
    out = 'dnn.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/dnn.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-imgcodecs-ImgcodecsTest-java', 
    out = 'ImgcodecsTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/imgcodecs/ImgcodecsTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-imgcodecs-Imgcodecs-java', 
    out = 'Imgcodecs.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/imgcodecs/Imgcodecs.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-imgcodecs-inl-hpp', 
    out = 'imgcodecs.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/imgcodecs.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-imgcodecs-txt', 
    out = 'imgcodecs.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/imgcodecs.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-videoio-VideoCaptureTest-java', 
    out = 'VideoCaptureTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/videoio/VideoCaptureTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-videoio-VideoWriter-java', 
    out = 'VideoWriter.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/VideoWriter.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-videoio-Videoio-java', 
    out = 'Videoio.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/Videoio.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-videoio-VideoCapture-java', 
    out = 'VideoCapture.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/videoio/VideoCapture.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-videoio-inl-hpp', 
    out = 'videoio.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/videoio.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-videoio-txt', 
    out = 'videoio.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/videoio.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-highgui-ImageWindow-java', 
    out = 'ImageWindow.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui/ImageWindow.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-highgui-HighGui-java', 
    out = 'HighGui.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/highgui/HighGui.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-SIFTFeatureDetectorTest-java', 
    out = 'SIFTFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIFTFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-MSERFeatureDetectorTest-java', 
    out = 'MSERFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/MSERFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-SURFFeatureDetectorTest-java', 
    out = 'SURFFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SURFFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-BruteForceSL2DescriptorMatcherTest-java', 
    out = 'BruteForceSL2DescriptorMatcherTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceSL2DescriptorMatcherTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-ORBFeatureDetectorTest-java', 
    out = 'ORBFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/ORBFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-BruteForceDescriptorMatcherTest-java', 
    out = 'BruteForceDescriptorMatcherTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceDescriptorMatcherTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-BruteForceHammingLUTDescriptorMatcherTest-java', 
    out = 'BruteForceHammingLUTDescriptorMatcherTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceHammingLUTDescriptorMatcherTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-SIMPLEBLOBFeatureDetectorTest-java', 
    out = 'SIMPLEBLOBFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIMPLEBLOBFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-FASTFeatureDetectorTest-java', 
    out = 'FASTFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/FASTFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-DENSEFeatureDetectorTest-java', 
    out = 'DENSEFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/DENSEFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-SIFTDescriptorExtractorTest-java', 
    out = 'SIFTDescriptorExtractorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SIFTDescriptorExtractorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-GFTTFeatureDetectorTest-java', 
    out = 'GFTTFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/GFTTFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-BruteForceL1DescriptorMatcherTest-java', 
    out = 'BruteForceL1DescriptorMatcherTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceL1DescriptorMatcherTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-BRIEFDescriptorExtractorTest-java', 
    out = 'BRIEFDescriptorExtractorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BRIEFDescriptorExtractorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-ORBDescriptorExtractorTest-java', 
    out = 'ORBDescriptorExtractorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/ORBDescriptorExtractorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-STARFeatureDetectorTest-java', 
    out = 'STARFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/STARFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-Features2dTest-java', 
    out = 'Features2dTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/Features2dTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-BruteForceHammingDescriptorMatcherTest-java', 
    out = 'BruteForceHammingDescriptorMatcherTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/BruteForceHammingDescriptorMatcherTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-SURFDescriptorExtractorTest-java', 
    out = 'SURFDescriptorExtractorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/SURFDescriptorExtractorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-FlannBasedDescriptorMatcherTest-java', 
    out = 'FlannBasedDescriptorMatcherTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/FlannBasedDescriptorMatcherTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-features2d-HARRISFeatureDetectorTest-java', 
    out = 'HARRISFeatureDetectorTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/features2d/HARRISFeatureDetectorTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-BOWImgDescriptorExtractor-java', 
    out = 'BOWImgDescriptorExtractor.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWImgDescriptorExtractor.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-FastFeatureDetector-java', 
    out = 'FastFeatureDetector.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/FastFeatureDetector.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-Feature2D-java', 
    out = 'Feature2D.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Feature2D.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-BRISK-java', 
    out = 'BRISK.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BRISK.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-BFMatcher-java', 
    out = 'BFMatcher.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BFMatcher.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-AgastFeatureDetector-java', 
    out = 'AgastFeatureDetector.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/AgastFeatureDetector.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-GFTTDetector-java', 
    out = 'GFTTDetector.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/GFTTDetector.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-DescriptorMatcher-java', 
    out = 'DescriptorMatcher.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/DescriptorMatcher.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-KAZE-java', 
    out = 'KAZE.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/KAZE.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-Features2d-java', 
    out = 'Features2d.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Features2d.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-AKAZE-java', 
    out = 'AKAZE.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/AKAZE.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-Params-java', 
    out = 'Params.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/Params.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-BOWTrainer-java', 
    out = 'BOWTrainer.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWTrainer.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-ORB-java', 
    out = 'ORB.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/ORB.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-MSER-java', 
    out = 'MSER.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/MSER.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-BOWKMeansTrainer-java', 
    out = 'BOWKMeansTrainer.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/BOWKMeansTrainer.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-features2d-FlannBasedMatcher-java', 
    out = 'FlannBasedMatcher.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/features2d/FlannBasedMatcher.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-features2d-inl-hpp', 
    out = 'features2d.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/features2d.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-features2d-txt', 
    out = 'features2d.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/features2d.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-calib3d-StereoBMTest-java', 
    out = 'StereoBMTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/StereoBMTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-calib3d-StereoSGBMTest-java', 
    out = 'StereoSGBMTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/StereoSGBMTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-calib3d-Calib3dTest-java', 
    out = 'Calib3dTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/calib3d/Calib3dTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-calib3d-StereoSGBM-java', 
    out = 'StereoSGBM.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoSGBM.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-calib3d-StereoBM-java', 
    out = 'StereoBM.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoBM.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-calib3d-StereoMatcher-java', 
    out = 'StereoMatcher.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/StereoMatcher.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-calib3d-Calib3d-java', 
    out = 'Calib3d.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/calib3d/Calib3d.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-calib3d-inl-hpp', 
    out = 'calib3d.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/calib3d.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-calib3d-txt', 
    out = 'calib3d.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/calib3d.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-video-BackgroundSubtractorMOGTest-java', 
    out = 'BackgroundSubtractorMOGTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/BackgroundSubtractorMOGTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-video-VideoTest-java', 
    out = 'VideoTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/VideoTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-test-org-opencv-test-video-KalmanFilterTest-java', 
    out = 'KalmanFilterTest.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/test/org/opencv/test/video/KalmanFilterTest.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-DualTVL1OpticalFlow-java', 
    out = 'DualTVL1OpticalFlow.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/DualTVL1OpticalFlow.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-BackgroundSubtractorMOG2-java', 
    out = 'BackgroundSubtractorMOG2.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractorMOG2.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-FarnebackOpticalFlow-java', 
    out = 'FarnebackOpticalFlow.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/FarnebackOpticalFlow.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-SparseOpticalFlow-java', 
    out = 'SparseOpticalFlow.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/SparseOpticalFlow.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-DenseOpticalFlow-java', 
    out = 'DenseOpticalFlow.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/DenseOpticalFlow.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-BackgroundSubtractor-java', 
    out = 'BackgroundSubtractor.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractor.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-Video-java', 
    out = 'Video.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/Video.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-KalmanFilter-java', 
    out = 'KalmanFilter.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/KalmanFilter.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-SparsePyrLKOpticalFlow-java', 
    out = 'SparsePyrLKOpticalFlow.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/SparsePyrLKOpticalFlow.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-java-org-opencv-video-BackgroundSubtractorKNN-java', 
    out = 'BackgroundSubtractorKNN.java', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/java/org/opencv/video/BackgroundSubtractorKNN.java $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-video-inl-hpp', 
    out = 'video.inl.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/video.inl.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-video-txt', 
    out = 'video.txt', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/video.txt $OUT', 
  )

genrule(
    name = 'gen-build-modules-java_bindings_generator-gen-cpp-opencv_jni-hpp', 
    out = 'opencv_jni.hpp', 
    cmd = 'cp $(location :gen-e04a3d040f07031b1d805a2bea3c425158cdba6b)/build/macos/modules/java_bindings_generator/gen/cpp/opencv_jni.hpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-ts-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/ts/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/ts/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/ts/$OUT', 
  )

genrule(
    name = 'gen-build-modules-core-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/core/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/core/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/core/$OUT', 
  )

genrule(
    name = 'gen-build-modules-imgproc-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/imgproc/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/imgproc/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/imgproc/$OUT', 
  )

genrule(
    name = 'gen-build-modules-imgcodecs-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/imgcodecs/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/imgcodecs/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/imgcodecs/$OUT', 
  )

genrule(
    name = 'gen-build-modules-videoio-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/videoio/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/videoio/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/videoio/$OUT', 
  )

genrule(
    name = 'gen-build-modules-highgui-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/highgui/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/highgui/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/highgui/$OUT', 
  )

genrule(
    name = 'gen-build-modules-core-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/core/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/core/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/core/$OUT', 
  )

genrule(
    name = 'gen-build-modules-flann-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/flann/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/flann/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/flann/$OUT', 
  )

genrule(
    name = 'gen-build-modules-flann-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/flann/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/flann/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/flann/$OUT', 
  )

genrule(
    name = 'gen-build-modules-imgproc-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/imgproc/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/imgproc/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/imgproc/$OUT', 
  )

genrule(
    name = 'gen-build-modules-imgproc-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/imgproc/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/imgproc/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/imgproc/$OUT', 
  )

genrule(
    name = 'gen-build-modules-ml-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/ml/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/ml/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/ml/$OUT', 
  )

genrule(
    name = 'gen-build-modules-ml-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/ml/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/ml/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/ml/$OUT', 
  )

genrule(
    name = 'gen-build-modules-objdetect-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/objdetect/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/objdetect/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/objdetect/$OUT', 
  )

genrule(
    name = 'gen-build-modules-objdetect-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/objdetect/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/objdetect/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/objdetect/$OUT', 
  )

genrule(
    name = 'gen-build-modules-objdetect-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/objdetect/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/objdetect/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/objdetect/$OUT', 
  )

genrule(
    name = 'gen-build-modules-photo-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/photo/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/photo/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/photo/$OUT', 
  )

genrule(
    name = 'gen-build-modules-photo-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/photo/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/photo/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/photo/$OUT', 
  )

genrule(
    name = 'gen-build-modules-photo-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/photo/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/photo/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/photo/$OUT', 
  )

genrule(
    name = 'gen-build-modules-viz-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/viz/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/viz/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/viz/$OUT', 
  )

genrule(
    name = 'gen-build-modules-viz-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/viz/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/viz/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/viz/$OUT', 
  )

genrule(
    name = 'gen-build-modules-dnn-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/dnn/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/dnn/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/dnn/$OUT', 
  )

genrule(
    name = 'gen-build-modules-dnn-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/dnn/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/dnn/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/dnn/$OUT', 
  )

genrule(
    name = 'gen-build-modules-dnn-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/dnn/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/dnn/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/dnn/$OUT', 
  )

genrule(
    name = 'gen-build-modules-imgcodecs-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/imgcodecs/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/imgcodecs/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/imgcodecs/$OUT', 
  )

genrule(
    name = 'gen-build-modules-imgcodecs-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/imgcodecs/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/imgcodecs/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/imgcodecs/$OUT', 
  )

genrule(
    name = 'gen-build-modules-videoio-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/videoio/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/videoio/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/videoio/$OUT', 
  )

genrule(
    name = 'gen-build-modules-videoio-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/videoio/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/videoio/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/videoio/$OUT', 
  )

genrule(
    name = 'gen-build-modules-highgui-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/highgui/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/highgui/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/highgui/$OUT', 
  )

genrule(
    name = 'gen-build-modules-features2d-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/features2d/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/features2d/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/features2d/$OUT', 
  )

genrule(
    name = 'gen-build-modules-features2d-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/features2d/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/features2d/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/features2d/$OUT', 
  )

genrule(
    name = 'gen-build-modules-features2d-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/features2d/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/features2d/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/features2d/$OUT', 
  )

genrule(
    name = 'gen-build-modules-calib3d-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/calib3d/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/calib3d/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/calib3d/$OUT', 
  )

genrule(
    name = 'gen-build-modules-calib3d-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/calib3d/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/calib3d/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/calib3d/$OUT', 
  )

genrule(
    name = 'gen-build-modules-calib3d-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/calib3d/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/calib3d/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/calib3d/$OUT', 
  )

genrule(
    name = 'gen-build-modules-shape-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/shape/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/shape/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/shape/$OUT', 
  )

genrule(
    name = 'gen-build-modules-shape-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/shape/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/shape/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/shape/$OUT', 
  )

genrule(
    name = 'gen-build-modules-stitching-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/stitching/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/stitching/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/stitching/$OUT', 
  )

genrule(
    name = 'gen-build-modules-stitching-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/stitching/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/stitching/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/stitching/$OUT', 
  )

genrule(
    name = 'gen-build-modules-stitching-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/stitching/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/stitching/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/stitching/$OUT', 
  )

genrule(
    name = 'gen-build-modules-video-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/video/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/video/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/video/$OUT', 
  )

genrule(
    name = 'gen-build-modules-video-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/video/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/video/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/video/$OUT', 
  )

genrule(
    name = 'gen-build-modules-video-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/video/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/video/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/video/$OUT', 
  )

genrule(
    name = 'gen-build-modules-videostab-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/videostab/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/videostab/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/videostab/$OUT', 
  )

genrule(
    name = 'gen-build-modules-videostab-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/videostab/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/videostab/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/videostab/$OUT', 
  )

genrule(
    name = 'gen-build-modules-superres-perf_precomp-hpp', 
    out = 'perf_precomp.hpp', 
    srcs = glob(["modules/superres/perf/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/superres/perf/perf_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/superres/$OUT', 
  )

genrule(
    name = 'gen-build-modules-superres-precomp-hpp', 
    out = 'precomp.hpp', 
    srcs = glob(["modules/superres/src/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/superres/src/precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/superres/$OUT', 
  )

genrule(
    name = 'gen-build-modules-superres-test_precomp-hpp', 
    out = 'test_precomp.hpp', 
    srcs = glob(["modules/superres/test/*.hpp"]), 
    cmd = 'cmake -E copy_if_different /home/gaetano/projects/opencv/modules/superres/test/test_precomp.hpp /home/gaetano/projects/opencv/build/macos/modules/superres/$OUT', 
  )

genrule(
    name = 'gen-920cb5d1bc711dd5760dc5388cae7201bbfdcb15', 
    out = 'out', 
    srcs = glob([
      "cmake/*.cmake", 
      "modules/core/src/opencl/*.cl"
    ]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/core && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/core && cmake -DMODULE_NAME=core -DCL_DIR=modules/core/src/opencl -DOUTPUT=build/macos/modules/core/opencl_kernels_core.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/core/opencl_kernels_core.cpp $OUT/build/macos/modules/core/opencl_kernels_core.cpp && cp $TMP/build/macos/modules/core/opencl_kernels_core.hpp $OUT/build/macos/modules/core/opencl_kernels_core.hpp', 
  )
genrule(
    name = 'gen-build-modules-core-opencl_kernels_core-cpp', 
    out = 'opencl_kernels_core.cpp', 
    cmd = 'cp $(location :gen-920cb5d1bc711dd5760dc5388cae7201bbfdcb15)/build/macos/modules/core/opencl_kernels_core.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-core-opencl_kernels_core-hpp', 
    out = 'opencl_kernels_core.hpp', 
    cmd = 'cp $(location :gen-920cb5d1bc711dd5760dc5388cae7201bbfdcb15)/build/macos/modules/core/opencl_kernels_core.hpp $OUT', 
  )

genrule(
    name = 'gen-0075e6c42802f268653572729efad59f63f3b55b', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/imgproc/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/imgproc && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/imgproc && cmake -DMODULE_NAME=imgproc -DCL_DIR=modules/imgproc/src/opencl -DOUTPUT=build/macos/modules/imgproc/opencl_kernels_imgproc.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/imgproc/opencl_kernels_imgproc.cpp $OUT/build/macos/modules/imgproc/opencl_kernels_imgproc.cpp && cp $TMP/build/macos/modules/imgproc/opencl_kernels_imgproc.hpp $OUT/build/macos/modules/imgproc/opencl_kernels_imgproc.hpp', 
  )
genrule(
    name = 'gen-build-modules-imgproc-opencl_kernels_imgproc-cpp', 
    out = 'opencl_kernels_imgproc.cpp', 
    cmd = 'cp $(location :gen-0075e6c42802f268653572729efad59f63f3b55b)/build/macos/modules/imgproc/opencl_kernels_imgproc.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-imgproc-opencl_kernels_imgproc-hpp', 
    out = 'opencl_kernels_imgproc.hpp', 
    cmd = 'cp $(location :gen-0075e6c42802f268653572729efad59f63f3b55b)/build/macos/modules/imgproc/opencl_kernels_imgproc.hpp $OUT', 
  )

genrule(
    name = 'gen-58bfc6659cc734848412649bd97109061cb1187e', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/photo/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/photo && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/photo && cmake -DMODULE_NAME=photo -DCL_DIR=modules/photo/src/opencl -DOUTPUT=build/macos/modules/photo/opencl_kernels_photo.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/photo/opencl_kernels_photo.cpp $OUT/build/macos/modules/photo/opencl_kernels_photo.cpp && cp $TMP/build/macos/modules/photo/opencl_kernels_photo.hpp $OUT/build/macos/modules/photo/opencl_kernels_photo.hpp', 
  )
genrule(
    name = 'gen-build-modules-photo-opencl_kernels_photo-cpp', 
    out = 'opencl_kernels_photo.cpp', 
    cmd = 'cp $(location :gen-58bfc6659cc734848412649bd97109061cb1187e)/build/macos/modules/photo/opencl_kernels_photo.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-photo-opencl_kernels_photo-hpp', 
    out = 'opencl_kernels_photo.hpp', 
    cmd = 'cp $(location :gen-58bfc6659cc734848412649bd97109061cb1187e)/build/macos/modules/photo/opencl_kernels_photo.hpp $OUT', 
  )

genrule(
    name = 'gen-d8bc571e30f9518531636594547ef68226e9c055', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/objdetect/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/objdetect && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/objdetect && cmake -DMODULE_NAME=objdetect -DCL_DIR=modules/objdetect/src/opencl -DOUTPUT=build/macos/modules/objdetect/opencl_kernels_objdetect.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/objdetect/opencl_kernels_objdetect.cpp $OUT/build/macos/modules/objdetect/opencl_kernels_objdetect.cpp && cp $TMP/build/macos/modules/objdetect/opencl_kernels_objdetect.hpp $OUT/build/macos/modules/objdetect/opencl_kernels_objdetect.hpp', 
  )
genrule(
    name = 'gen-build-modules-objdetect-opencl_kernels_objdetect-cpp', 
    out = 'opencl_kernels_objdetect.cpp', 
    cmd = 'cp $(location :gen-d8bc571e30f9518531636594547ef68226e9c055)/build/macos/modules/objdetect/opencl_kernels_objdetect.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-objdetect-opencl_kernels_objdetect-hpp', 
    out = 'opencl_kernels_objdetect.hpp', 
    cmd = 'cp $(location :gen-d8bc571e30f9518531636594547ef68226e9c055)/build/macos/modules/objdetect/opencl_kernels_objdetect.hpp $OUT', 
  )

genrule(
    name = 'gen-581accf8391b34b34bc63bd8b3ae69526f9f49a2', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/dnn/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/dnn && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/dnn && cmake -DMODULE_NAME=dnn -DCL_DIR=modules/dnn/src/opencl -DOUTPUT=build/macos/modules/dnn/opencl_kernels_dnn.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/dnn/opencl_kernels_dnn.cpp $OUT/build/macos/modules/dnn/opencl_kernels_dnn.cpp && cp $TMP/build/macos/modules/dnn/opencl_kernels_dnn.hpp $OUT/build/macos/modules/dnn/opencl_kernels_dnn.hpp', 
  )
genrule(
    name = 'gen-build-modules-dnn-opencl_kernels_dnn-cpp', 
    out = 'opencl_kernels_dnn.cpp', 
    cmd = 'cp $(location :gen-581accf8391b34b34bc63bd8b3ae69526f9f49a2)/build/macos/modules/dnn/opencl_kernels_dnn.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-dnn-opencl_kernels_dnn-hpp', 
    out = 'opencl_kernels_dnn.hpp', 
    cmd = 'cp $(location :gen-581accf8391b34b34bc63bd8b3ae69526f9f49a2)/build/macos/modules/dnn/opencl_kernels_dnn.hpp $OUT', 
  )

genrule(
    name = 'gen-fd18112f6d09e16f4797d282e0013423b9498d7f', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/features2d/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/features2d && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/features2d && cmake -DMODULE_NAME=features2d -DCL_DIR=modules/features2d/src/opencl -DOUTPUT=build/macos/modules/features2d/opencl_kernels_features2d.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/features2d/opencl_kernels_features2d.cpp $OUT/build/macos/modules/features2d/opencl_kernels_features2d.cpp && cp $TMP/build/macos/modules/features2d/opencl_kernels_features2d.hpp $OUT/build/macos/modules/features2d/opencl_kernels_features2d.hpp', 
  )
genrule(
    name = 'gen-build-modules-features2d-opencl_kernels_features2d-cpp', 
    out = 'opencl_kernels_features2d.cpp', 
    cmd = 'cp $(location :gen-fd18112f6d09e16f4797d282e0013423b9498d7f)/build/macos/modules/features2d/opencl_kernels_features2d.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-features2d-opencl_kernels_features2d-hpp', 
    out = 'opencl_kernels_features2d.hpp', 
    cmd = 'cp $(location :gen-fd18112f6d09e16f4797d282e0013423b9498d7f)/build/macos/modules/features2d/opencl_kernels_features2d.hpp $OUT', 
  )

genrule(
    name = 'gen-879fd49d256f41e47cb2698f17cffe9c83f359d2', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/calib3d/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/calib3d && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/calib3d && cmake -DMODULE_NAME=calib3d -DCL_DIR=modules/calib3d/src/opencl -DOUTPUT=build/macos/modules/calib3d/opencl_kernels_calib3d.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/calib3d/opencl_kernels_calib3d.cpp $OUT/build/macos/modules/calib3d/opencl_kernels_calib3d.cpp && cp $TMP/build/macos/modules/calib3d/opencl_kernels_calib3d.hpp $OUT/build/macos/modules/calib3d/opencl_kernels_calib3d.hpp', 
  )
genrule(
    name = 'gen-build-modules-calib3d-opencl_kernels_calib3d-cpp', 
    out = 'opencl_kernels_calib3d.cpp', 
    cmd = 'cp $(location :gen-879fd49d256f41e47cb2698f17cffe9c83f359d2)/build/macos/modules/calib3d/opencl_kernels_calib3d.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-calib3d-opencl_kernels_calib3d-hpp', 
    out = 'opencl_kernels_calib3d.hpp', 
    cmd = 'cp $(location :gen-879fd49d256f41e47cb2698f17cffe9c83f359d2)/build/macos/modules/calib3d/opencl_kernels_calib3d.hpp $OUT', 
  )

genrule(
    name = 'gen-5f8536be81693a267921b3c199dbd06a1078701e', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/stitching/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/stitching && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/stitching && cmake -DMODULE_NAME=stitching -DCL_DIR=modules/stitching/src/opencl -DOUTPUT=build/macos/modules/stitching/opencl_kernels_stitching.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/stitching/opencl_kernels_stitching.cpp $OUT/build/macos/modules/stitching/opencl_kernels_stitching.cpp && cp $TMP/build/macos/modules/stitching/opencl_kernels_stitching.hpp $OUT/build/macos/modules/stitching/opencl_kernels_stitching.hpp', 
  )
genrule(
    name = 'gen-build-modules-stitching-opencl_kernels_stitching-cpp', 
    out = 'opencl_kernels_stitching.cpp', 
    cmd = 'cp $(location :gen-5f8536be81693a267921b3c199dbd06a1078701e)/build/macos/modules/stitching/opencl_kernels_stitching.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-stitching-opencl_kernels_stitching-hpp', 
    out = 'opencl_kernels_stitching.hpp', 
    cmd = 'cp $(location :gen-5f8536be81693a267921b3c199dbd06a1078701e)/build/macos/modules/stitching/opencl_kernels_stitching.hpp $OUT', 
  )

genrule(
    name = 'gen-814bc8f6366800660d445d79bd640d5510655444', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/video/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/video && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/video && cmake -DMODULE_NAME=video -DCL_DIR=modules/video/src/opencl -DOUTPUT=build/macos/modules/video/opencl_kernels_video.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/video/opencl_kernels_video.cpp $OUT/build/macos/modules/video/opencl_kernels_video.cpp && cp $TMP/build/macos/modules/video/opencl_kernels_video.hpp $OUT/build/macos/modules/video/opencl_kernels_video.hpp', 
  )
genrule(
    name = 'gen-build-modules-video-opencl_kernels_video-cpp', 
    out = 'opencl_kernels_video.cpp', 
    cmd = 'cp $(location :gen-814bc8f6366800660d445d79bd640d5510655444)/build/macos/modules/video/opencl_kernels_video.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-video-opencl_kernels_video-hpp', 
    out = 'opencl_kernels_video.hpp', 
    cmd = 'cp $(location :gen-814bc8f6366800660d445d79bd640d5510655444)/build/macos/modules/video/opencl_kernels_video.hpp $OUT', 
  )

genrule(
    name = 'gen-010f4a6e2332eeb63feefa820e50cdb00e7ba32b', 
    out = 'out', 
    srcs = glob(["cmake/*.cmake","modules/superres/src/opencl/*.cl"]), 
    cmd = 'mkdir -p $OUT && mkdir -p $OUT/build/macos/modules/superres && cp -r $SRCDIR/* $TMP && cd $TMP && mkdir -p build/macos/modules/superres && cmake -DMODULE_NAME=superres -DCL_DIR=modules/superres/src/opencl -DOUTPUT=build/macos/modules/superres/opencl_kernels_superres.cpp -P cmake/cl2cpp.cmake && cp $TMP/build/macos/modules/superres/opencl_kernels_superres.cpp $OUT/build/macos/modules/superres/opencl_kernels_superres.cpp && cp $TMP/build/macos/modules/superres/opencl_kernels_superres.hpp $OUT/build/macos/modules/superres/opencl_kernels_superres.hpp', 
  )
genrule(
    name = 'gen-build-modules-superres-opencl_kernels_superres-cpp', 
    out = 'opencl_kernels_superres.cpp', 
    cmd = 'cp $(location :gen-010f4a6e2332eeb63feefa820e50cdb00e7ba32b)/build/macos/modules/superres/opencl_kernels_superres.cpp $OUT', 
  )

genrule(
    name = 'gen-build-modules-superres-opencl_kernels_superres-hpp', 
    out = 'opencl_kernels_superres.hpp', 
    cmd = 'cp $(location :gen-010f4a6e2332eeb63feefa820e50cdb00e7ba32b)/build/macos/modules/superres/opencl_kernels_superres.hpp $OUT', 
  )
