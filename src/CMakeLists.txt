add_executable(blink
    main.c
)

target_link_libraries(blink pico_stdlib freertos pico_cyw43_arch_none)
pico_add_extra_outputs(blink)