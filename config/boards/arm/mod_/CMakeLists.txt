target_sources_ifdef(CONFIG_CAPS_LOCK_LED app PRIVATE lckc.c)
#target_sources_ifdef(CONFIG_NUM_LOCK_LED app PRIVATE lckn.c)
#target_sources_ifdef(CONFIG_SCROLL_LOCK_LED app PRIVATE lcks.c)

zephyr_include_directories(include)