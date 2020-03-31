package(default_visibility = ["//visibility:public"])

cc_library(
    name = "qt_lib_charts",
    srcs = ["libQt5Charts.so.5"]
)
cc_library(
    name = "qt_lib_core",
    srcs = ["libQt5Core.so.5","libQt5Core.so", "libicui18n.so.60", "libicui18n.so.60.2", "libicuuc.so.60", "libicuuc.so.60.2", "libicudata.so.60", "libicudata.so.60.2",]
)
cc_library(
    name = "qt_lib_widget",
    srcs = ["libQt5Widgets.so.5","libQt5Widgets.so",],
    deps = [":qt_lib_core", "qt_lib_gui",],
)
cc_library(
    name = "qt_lib_gui",
    srcs = ["libQt5Gui.so"]
)