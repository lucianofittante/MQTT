idf_component_register(SRCS "station_example_main.c" "C:/Users/lucho/Desktop/Proyectos_ESP_en_C/Esp_Idf_MQTT/esp32-DHT11/dht11.c"
                    INCLUDE_DIRS "." "C:/Users/lucho/Desktop/Proyectos_ESP_en_C/Esp_Idf_MQTT/esp32-DHT11/include"
)

spiffs_create_partition_image(storage ../data FLASH_IN_PROJECT)
