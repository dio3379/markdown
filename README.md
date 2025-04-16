## **多层廓线**

1. **divergence.nc** → d

    **散度**：描述风场中空气的“发散”或“汇聚”程度。正散度表示空气在水平上发散，负散度则表示空气在汇聚。

2. **fraction_of_cloud_cover.nc** → cc

    **云覆盖率**：表示天空中被云层覆盖的比例，通常是 0 到 1 之间的小数，0 表示完全晴空，1 表示完全多云。

3. **geopotential.nc** → z

    **位势高度**：是重力势能与质量之比，常用于大气动力学中衡量高度。可以用来描述等压面在空间中的高度。

4. **ozone_mass_mixing_ratio.nc** → o3

    **臭氧质量混合比**：表示单位质量的空气中所含臭氧的质量，常用于分析臭氧层分布和空气质量。

5. **potential_vorticity.nc** → pv

    **位涡**：结合了大气旋转（涡度）与稳定性（层结）的物理量，是天气系统分析中非常关键的参数。

6. **relative_humidity.nc** → r

    **相对湿度**：空气中实际水汽含量与饱和水汽含量的比值，反映空气的潮湿程度。

7. **specific_cloud_ice_water_content.nc** → ciwc

    **云冰含量（比值）**：单位质量的空气中所含云冰（水汽凝结成冰晶）的质量。

8. **specific_cloud_liquid_water_content.nc** → clwc

    **云液态水含量（比值）**：单位质量的空气中所含云液态水（水汽凝结但未结冰）的质量。

9. **specific_humidity.nc** → q

    **比湿**：单位质量的空气中所含水汽的质量，反映湿润程度的一个基本参数。

10. **specific_rain_water_content.nc** → crwc

    **雨水含量（比值）**：单位质量的空气中实际降水（雨水）的质量，用于模拟降水过程。

11. **temperature.nc** → t

    **温度**：空气的温度，通常以开尔文或摄氏度为单位，是气象模拟中最基本的变量之一。

12. **u_component_of_wind.nc** → u

    **风的 U 分量（东西向风速）**：表示东西方向上的风速，正值为西风，负值为东风。

13. **vertical_velocity.nc**

    **垂直速度**：空气在垂直方向上的运动速度，反映上升或下沉气流的强度。

14. **vorticity.nc** → vo

    **涡度**：表示空气旋转程度的物理量，是判断气旋系统的重要参数。

15. **v_component_of_wind.nc** → v

    **风的 V 分量（南北向风速）**：表示南北方向上的风速，正值为南风，负值为北风。

## **单层气象场**

1. **10m_u_component_of_wind.nc** → 10u

    **10 米高度的风的 U 分量（东西向分量）**：表示在 10 米高度上风的东西方向分量。

2. **10m_v_component_of_wind.nc** → 10v

    **10 米高度的风的 V 分量（南北向分量）**：表示在 10 米高度上风的南北方向分量。

3. **100m_u_component_of_wind.nc** → 100u

    **100 米高度的风的 U 分量（东西向分量）**：多用于风能分析等高空风研究。

4. **100m_v_component_of_wind.nc** → 100v

    **100 米高度的风的 V 分量（南北向分量）**

5. **2m_temperature.nc** → t2m

    **2 米高度的气温**：表示接近地面的空气温度，常用作地表温度代表。

6. **2m_dewpoint_temperature.nc** → d2m

    **2 米高度的露点温度**：用于估算空气湿度，判断是否可能形成露水或雾。

7. **mean_sea_level_pressure.nc** → msl

    **海平面气压（平均）**：对比分析天气系统（如气旋、反气旋）非常重要。

8. **surface_pressure.nc** → sp

    **地面气压**：实际地表测得的大气压力。

9. **total_precipitation.nc** → tp

    **总降水量**：包含雨、雪等降水形式的总和。

10. **mean_surface_downward_long_wave_radiation_flux.nc** → avg_sdlwrf

    **地表向下长波辐射平均通量**：通常是来自大气的热辐射。

11. **mean_surface_downward_short_wave_radiation_flux.nc** → avg_sdswrf

    **地表向下短波辐射平均通量**：主要是太阳辐射。

12. **mean_surface_net_long_wave_radiation_flux.nc** → avg_snlwrf

    **地表净长波辐射平均通量**：地面释放与接收长波的差值。

13. **mean_surface_net_short_wave_radiation_flux.nc** → avg_snswrf

    **地表净短波辐射平均通量**：接收的太阳辐射减去反射部分后的剩余能量。

14. **mean_top_net_long_wave_radiation_flux.nc** → avg_tnlwrf

    **大气顶层净长波辐射平均通量**：衡量地球向外太空释放的热量。

15. **high_cloud_cover.nc** → hcc

    **高云覆盖率**

16. **medium_cloud_cover.nc** → mcc

    **中云覆盖率**

17. **low_cloud_cover.nc** → lcc

    **低云覆盖率**

18. **total_cloud_cover.nc** → tcc

    **总云覆盖率**：影响地表能量平衡、降水等。

19. **total_column_cloud_liquid_water.nc** → tclw

    **整层云液态水含量**：云中水滴总量的估计，常用于降水预测。

20. **vertical_integral_of_eastward_cloud_liquid_water_flux.nc** → vilwe

    **云液态水向东通量的垂直积分**

21. **vertical_integral_of_northward_cloud_liquid_water_flux.nc** → vilwn

    **云液态水向北通量的垂直积分**

22. **vertical_integral_of_eastward_water_vapour_flux.nc** → viwve

    **水汽向东通量的垂直积分**

23. **vertical_integral_of_northward_water_vapour_flux.nc** → viwvn

    **水汽向北通量的垂直积分**：这些数据用于分析水汽运输路径、云形成机制等。

24. **boundary_layer_height.nc** → blh

    **边界层高度**：描述大气边界层（地面与自由大气之间的混合层）厚度。

25. **instantaneous_moisture_flux.nc** → ie

    **瞬时水汽通量**：用于瞬时天气系统（如锋面）分析。

