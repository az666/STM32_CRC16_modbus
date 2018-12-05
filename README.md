# STM32_CRC16_modbus
STM32modbus_CRC16校验
> 直接调用函数即可：例如：
> uint8_t crc16_data[] = {0x01, 0x46, 0x00, 0x00, 0x00, 0x01, 0x02, 0x00, 0x64};
>  printf(" modbus crc16tablefast test, expected value : 0xd825, calculate value : 0x%x\n", crc16tablefast(crc16_data, sizeof(crc16_data)));
