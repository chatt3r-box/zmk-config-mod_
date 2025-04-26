target_sources_ifdef(CONFIG_CAPSLOCK_LED app PRIVATE lckc.c)
target_sources_ifdef(CONFIG_NUMLOCK_LED app PRIVATE lckn.c)
target_sources_ifdef(CONFIG_SCROLLLOCK_LED app PRIVATE lcks.c)

zephyr_include_directories(include)