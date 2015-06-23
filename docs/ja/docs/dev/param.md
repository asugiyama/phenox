# パラメーター一覧
### float duty_hover
ホバー状態 (`PX_HOVER`) での、基本推力を表します。この基本推力に対して、`pgain_sonar_tz`, `dgain_sonar_tz` で指定したゲインに応じて高度制御が行われます。積載重量に応じて、1200 から 1400 程度の値が 目安です。

### float duty_hover_max
ホバー状態 (`PX_HOVER`) での、最大推力を表します。`duty_hover+150` から `duty_hover+250`	 程度の値が目安です。

### float duty_hover_min

### float duty_bias_front

### float pgain_vision_tx

### float uptime_max

### float pgain_degx

### float pgain_degy

### float dgain_degx

### float dgain_degy

### float dgain_degz
機体軸 Z に対する回転運動の微分ゲインです。比例ゲインに応じて適宜変更してください。

### int pwm_or_servo
