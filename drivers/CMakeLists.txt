zephyr_include_directories(include)

add_subdirectory_ifdef(CONFIG_USE_ALIF_HAL_OSPI ospi)

add_subdirectory_ifdef(CONFIG_CLOCK_CONTROL_ALIF clock_control)

add_subdirectory_ifdef(CONFIG_ARM_ETHOS_U       ethos_u)
