---
order: 8
title: Модуль 8xTHV (THM42)
---

### **Описание**

Модуль 8xTHV включает 8 каналов для подключения любых типов термопар, а также датчиков типа Pt100. Дистанционная компенсация холодного спая обеспечивается подмодулем (который зависит от типа термопары), а линеаризация -- платой нормирования сигнала. Модуль также оснащен откалиброванным источником тока 0,2 мА для возбуждения датчика Pt100.

Используемые с модулем адаптеры содержат пару распространенных мини-разъемов термопар E, J, K и T (другие типы доступны по запросу) со схемой компенсации холодного спая. Еще один адаптер оснащен парой разъемов LEMO® для датчиков Pt100. К модулю 8xTHV можно подключить любую комбинацию соответствующих адаптеров.

Модуль 8xTHV также оснащен 8 каналами для измерения входных сигналов напряжения до ±10 В. Модуль можно использовать:

•           для измерений с термопарами E, J, K и T (другие типы доступны по запросу)

•           при использовании датчиков Pt100 в режиме постоянного тока

•           с любым источником напряжения до ±10 В в режиме ввода напряжения



![](./8xthv-thm42.png){width=915px height=350px}



### **Функции**

<div class="table-wrapper">
  <table style="border-collapse: collapse; width: 100%;">
    <tbody>
      
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px; vertical-align: top;">
          <ul style="margin: 0; padding-left: 1.2em;">
            <li>8 каналов</li>
            <li>Три входных режима:
                <ul style="padding-left: 1.5em; margin-top: 4px; margin-bottom: 4px;">
                    <li>Термопары</li>
                    <li>Измерение температуры с датчиком Pt100</li>
                    <li>Режим входного сигнала напряжения</li>
                </ul>
            </li>
            <li>Поддержка TEDS IEEE 1451.4 V0.9, V1.0</li>
            <li>Разрешение 24 бит, частота дискретизации 6,4 Квыб/с на канал, полоса пропускания 2,5 кГц</li>
            <li>Входные диапазоны: &plusmn;100 мВ и &plusmn;10 В</li>
          </ul>
        </td>
        <td style="border: 1px solid #ccc; padding: 8px; vertical-align: top;">
          <ul style="margin: 0; padding-left: 1.2em;">
            <li>Ток возбуждения Pt100: 0,2 мА</li>
            <li>Отслеживание разомкнутого контура кабеля</li>
            <li>Цепь целостности сигнала и защита от перегрузки</li>
            <li>Возможность выбора цифровых фильтров</li>
            <li>Дифференциальное входное сопротивление 2 МОм</li>
            <li>7-контактные разъемы LEMO® EHG 0B</li>
          </ul>
        </td>
      </tr>
      
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Входы</th>
        <td style="border: 1px solid #ccc; padding: 8px;">Термопара и Pt100</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Датчики</th>
        <td style="border: 1px solid #ccc; padding: 8px;">Любая комбинация термопары и Pt100, однако для каждой пары каналов необходимо использовать датчики одного типа.</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Линеаризация</th>
        <td style="border: 1px solid #ccc; padding: 8px;">
            Линеаризация термопары по типам:
            <ul style="margin: 4px 0 0 20px; padding: 0;">
                <li>Хромель/константан (E, NiCr-CuNi)</li>
                <li>Железо/константан (J, Fe-CuNi)</li>
                <li>Хромель/алюмель® (K, NiCr-NiAl)</li>
                <li>Медь/константан (T, Cu-CuNi)</li>
            </ul>
        </td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Возбуждение</th>
        <td style="border: 1px solid #ccc; padding: 8px;">Ток возбуждения 0,2 мА для Pt100 и компенсации холодного спая. Встроенное отслеживание ухода и смещения.</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Макс. напряжение в синфазном режиме</th>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;7 В</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Подмодули</th>
        <td style="border: 1px solid #ccc; padding: 8px;">Кабель между модулем и проводом датчика с корпусом, включающим TEDS, компенсацию холодного спая и разъем датчика. Цветовая кодировка по типу термопары.</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Калибровка модуля</th>
        <td style="border: 1px solid #ccc; padding: 8px;">Внутренняя калибровка амплитуды и фазы</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Погрешность на фазу<br><small>Каналы в сходном диапазоне</small></th>
        <td style="border: 1px solid #ccc; padding: 8px;">Стандартно: &lt; 1,5&deg; при 1 кГц</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Защита</th>
        <td style="border: 1px solid #ccc; padding: 8px;">ЭСР 2 кВ</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Гальваническая изоляция</th>
        <td style="border: 1px solid #ccc; padding: 8px;">50 В</td>
      </tr>
    </tbody>
  </table>
</div>




### **Характеристики**

<div class="table-wrapper">
  <table style="width: 100%; border-collapse: collapse;">
    <tbody>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;">Полоса пропускания</th>
        <td colspan="2" style="border: 1px solid #ccc; padding: 8px;">Пост. ток до 2,9 кГц</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;">Максимальная частота дискретизации на канал</th>
        <td colspan="2" style="border: 1px solid #ccc; padding: 8px;">6,4 Квыб/с</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;">Другие значения частоты дискретизации</th>
        <td colspan="2" style="border: 1px solid #ccc; padding: 8px;">Доступно через цифровые ФНЧ и децимацию</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;">АЦП</th>
        <td colspan="2" style="border: 1px solid #ccc; padding: 8px;">24 бит</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;">Передача данных</th>
        <td colspan="2" style="border: 1px solid #ccc; padding: 8px;">16/24 бит</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;">Диапазоны входного напряжения (пик)</th>
        <td colspan="2" style="border: 1px solid #ccc; padding: 8px;">&plusmn;100 мВ, &plusmn;10 В</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; vertical-align: top;">Параметры входного смещения</th>
        <td style="border: 1px solid #ccc; padding: 8px;"><strong>Дифференциальное смещение (балансируемое смещение)</strong></td>
        <td style="border: 1px solid #ccc; padding: 8px;">Положительный и отрицательный входы сигнала подключены по линии 1 МОм к плавающему заземлению.</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;">Входное сопротивление</th>
        <td colspan="2" style="border: 1px solid #ccc; padding: 8px;">2 МОм || 22 нФ</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: middle;" rowspan="2">Погрешность на фазу<br><small>Каналы в сходном диапазоне</small></th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Гарантировано</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Стандартно</th>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">&lt; 0,5&deg; при 1 кГц</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&lt; 0,1&deg; при 1 кГц</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: middle;" rowspan="2">Возбуждение током</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Режим возбуждения</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">% режима возбуждения + мкА</th>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">200 мкА</td>
        <td style="border: 1px solid #ccc; padding: 8px;">0,3% + 1,7 мкА</td>
      </tr>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: middle;" rowspan="3">Точность напряжения</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Входной диапазон (пик)</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">% диапазона</th>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;100 мВ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">0,3%</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;10 В</td>
        <td style="border: 1px solid #ccc; padding: 8px;">0,1%</td>
      </tr>
    </tbody>
  </table>
</div>

<div class="table-wrapper">
  <table style="width: 100%; border-collapse: collapse;">
    <thead>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Характеристика</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: center; ">Тип термопары</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: center; ">Диапазон</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: center; ">Температура (°C)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: top;" rowspan="20">Погрешность по температуре</th>
        <td style="border: 1px solid #ccc; padding: 8px; text-align: center; vertical-align: middle;" rowspan="4">E</td>
        <td style="border: 1px solid #ccc; padding: 8px;">от -85 °C до -25 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3,6 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от -25 °C до 350 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">2,5 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 350 °C до 650 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3,0 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 650 °C до 780 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">2,4 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px; text-align: center; vertical-align: middle;" rowspan="2">J</td>
        <td style="border: 1px solid #ccc; padding: 8px;">от 0 °C до 150 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">2,5 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 150 °C до 750 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3,0 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px; text-align: center; vertical-align: middle;" rowspan="4">K</td>
        <td style="border: 1px solid #ccc; padding: 8px;">от -55 °C до -25 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">2,5 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от -25 °C до 120 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3,6 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 120 °C до 1000 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3,6 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 1000 °C до 1250 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">4,2 °C</td>
      </tr>
     
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px; text-align: center; vertical-align: middle;" rowspan="4">T</td>
        <td style="border: 1px solid #ccc; padding: 8px;">от -160 °C до -150 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">7,3 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от -150 °C до 0 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">4,8 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 0 °C до 120 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3,8 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 120 °C до 350 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3,2 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px; text-align: center; vertical-align: middle;" rowspan="5">Pt100</td>
        <td style="border: 1px solid #ccc; padding: 8px;">от -195 °C до 0 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">1,5 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 0 °C до 100 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">2,1 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 200 °C до 300 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">3 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 300 °C до 630 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">5,5 °C</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 630 °C до 800 °C</td>
        <td style="border: 1px solid #ccc; padding: 8px;text-align: center; ">6,4 °C</td>
      </tr>
    </tbody>
  </table>
</div>


<div class="table-wrapper">
  <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px;">
    <thead>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Характеристика</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Диапазон частот</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Входной диапазон (пик)</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Гарантировано</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Стандартно</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: middle;" rowspan="2">Шум<br><small>Оконечная нагрузка<br>входа — резистор<br>50 Ом</small></th>
        <td style="border: 1px solid #ccc; padding: 8px;">от 10 Гц до 2,9 кГц</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;100 мВ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&lt; 1,6 мкВ СКЗ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&lt; 1 мкВ СКЗ</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">от 10 Гц до 2,9 кГц</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;10 В</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&lt; 76 мкВ СКЗ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&lt; 53 мкВ СКЗ</td>
      </tr>
    </tbody>
  </table>

  <table style="width: 100%; border-collapse: collapse; margin-bottom: 20px;">
    <thead>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Характеристика</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Частота дискретизации</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Входной диапазон (пик)</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Неравномерность амплитудной хар-ки<br><small>(уровень входного сигнала 100% от полного диапазона)</small></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: middle;" rowspan="2">Неравномерность амплитудной хар-ки<br><small>Относительно 1 кГц<br><br>Измерено до 0,39 × частота дискретизации</small></th>
        <td style="border: 1px solid #ccc; padding: 8px;">6,4 Квыб/с</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;100 мВ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">-0,65 дБ</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">6,4 Квыб/с</td>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;10 В</td>
        <td style="border: 1px solid #ccc; padding: 8px;">-0,60 дБ</td>
      </tr>
    </tbody>
  </table>

  <table style="width: 100%; border-collapse: collapse;">
    <thead>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Характеристика</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Входной диапазон (пик)</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Гарантировано</th>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left; ">Стандартно</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th style="border: 1px solid #ccc; padding: 8px; text-align: left;  vertical-align: middle;" rowspan="2">Взаимное влияние</th>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;100 мВ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">92 дБ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">97 дБ</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ccc; padding: 8px;">&plusmn;10 В</td>
        <td style="border: 1px solid #ccc; padding: 8px;">71 дБ</td>
        <td style="border: 1px solid #ccc; padding: 8px;">76 дБ</td>
      </tr>
    </tbody>
  </table>
</div>




### **Функциональная схема на канал**

![](./8xthv-thm42-6.png){width=915px height=350px}

##### *Обзор функций одного канала 8xTHV.*


