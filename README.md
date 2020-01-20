# vhdl_coding_guidelines

|    **Номер** |	1.1 |
|-------------:|:-----|
| **Описание** | Используйте строчные буквы для всех ключевых слов языка программирования VHDL и для все типов данных. |
|   **Пример** | signal sig_name : std_logic;<br>~~SIGNAL sig_name : Std_Logic;~~ |


```vhdl
signal sig_name : std_logic;
SIGNAL sig_name : Std_Logic;
```

~~~
asdda
~~~

-------


``` SIGNAL sig_name : Std_Logic;```

```vhdl
port map(
  clk => clk,
  data => spi_data,
  enable => spi_enable,
  busy => wait
);
```

<span style="color:blue">some *blue* text</span>.
