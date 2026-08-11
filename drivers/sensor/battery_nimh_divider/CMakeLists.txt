if(CONFIG_COOL642TB_BATTERY_NIMH_DIVIDER)
  zephyr_library()
  zephyr_library_sources(battery_nimh_divider.c)
endif()
