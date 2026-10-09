% ... (предыдущие формулы 1-10) ...

% 11. Кольцевые напряжения
\sigma_{\text{кц}}^{\text{н}} = \frac{pD_{\text{вн}}}{2\delta_{\text{н}}}.

% 12. Условие прочности
\sigma_{\text{кц}}^{\text{н}} \le \frac{m}{0{,}9k_{\text{н}}} R_2^{\text{н}},

% 13. Коэффициент psi_1
\psi_1 = \sqrt{1 - 0{,}75 \left( \frac{\sigma_{\text{кц}}^{\text{н}}}{\frac{m}{0{,}9k_{\text{н}}} R_2^{\text{н}}} \right)^2} - 0{,}5 \frac{\sigma_{\text{кц}}^{\text{н}}}{\frac{m}{0{,}9k_{\text{н}}} R_2^{\text{н}}},

% 14. Суммарные продольные напряжения
\sigma_{\text{пр}}^{\text{н}} = \mu \sigma_{\text{кц}}^{\text{н}} - \alpha E \Delta t \pm \frac{ED_{\text{н}}}{2\rho},

% 15. Проверка прочности
\left| \sigma_{\text{пр}}^{\text{н}} \right| \le \psi_1 \frac{m}{0{,}9k_{\text{н}}} R_2^{\text{н}};

% 16. Условие устойчивости
1{,}5D_{\text{н}} \le 2b \ge 1{,}5 \text{ м}

% 17. Полная высота насыпи
h_2 = h_1 - \left( b + h_0 \operatorname{ctg} \alpha_{\text{н}} - 0{,}5 h_1 \right) \operatorname{tg} \left( 45^\circ - \frac{\varphi_{\text{гр}}}{2} \right)

% 18. Среднее давление грунта
p_{\text{гр}} = n_{\text{гр}} \gamma_{\text{гр}} \frac{h_0 \left( b + 0{,}5 h_0 \operatorname{ctg} \alpha_{\text{н}} \right)}{b + h_0 \operatorname{ctg} \alpha_{\text{н}}}

% 19. Активное сопротивление
E_{\text{акт}} = \frac{n_{\text{гр}} \gamma_{\text{гр}} h_1^2}{2} \operatorname{tg}^2 \left( 45^\circ - \frac{\varphi_{\text{гр}}}{2} \right) + p_{\text{гр}} h_1 \operatorname{tg}^2 \left( 45^\circ - \frac{\varphi_{\text{гр}}}{2} \right)

% 20. Пассивное сопротивление
E_1 = \frac{n_{\text{гр}} \gamma_{\text{гр}} \left( h_1^2 - h_2^2 \right)}{2} \operatorname{tg}^2 \left( 45^\circ + \frac{\varphi_{\text{гр}}}{2} \right) + p_{\text{гр}} h_1 \operatorname{tg}^2 \left( 45^\circ + \frac{\varphi_{\text{гр}}}{2} \right) + 2 n_{\text{гр}} c_{\text{гр}} (h_1 - h_2) \operatorname{tg} \left( 45^\circ + \frac{\varphi_{\text{гр}}}{2} \right);

% 21. Составляющая E_2
E_2 = q_{\text{гр}} \operatorname{tg} \varphi_{\text{гр}}

% 22. Сопротивление горизонтальному перемещению
q_{\text{гор}} = E_1 + E_2

% 23. Предельное касательное напряжение
\tau_{\text{пр}} = p_{\text{гр}} \operatorname{tg} \varphi_{\text{гр}} + c_{\text{гр}}

% 24. Сопротивление продольным перемещениям
p_0 = p D_{\text{н}} \tau_{\text{пр}}

% 25. Критическое усилие
N_{\text{кр}} = 3{,}97 \sqrt[11]{p_0^2 q_{\text{гор}}^4 F^2 E^5 I^3}

% 26. Условие устойчивости
S \le \frac{m}{1{,}1} N_{\text{кр}}

% 27. Половина ширины насыпи
a = b + \frac{H}{\operatorname{tg} \alpha_{\text{н}}}

% 28. Предельное сопротивление сдвигу
q_{\text{сдв}} = n_{\text{гр}} \gamma_{\text{гр}} f_{\text{гр}} H \frac{(2a - D_{\text{н}}) + (2b - D_{\text{н}})}{4} + f_{\text{гр}} \left[ q_{\text{гр}} + n_{\text{гр}} \gamma_{\text{гр}} D_{\text{н}} (H - D_{\text{н}}) \right] + n_{\text{гр}} c_{\text{гр}} \frac{2b - D_{\text{н}}}{2}.

% 29. Условие устойчивости на сдвиг
q_{\text{сдв}} \ge \frac{k_{\text{сдв}} S}{\rho}

% 30. Коэффициент k_alpha
\text{при } \alpha_{\text{в}} \le 45^\circ \quad k_\alpha = 1
\text{при } \alpha_{\text{в}} > 45^\circ \quad k_\alpha = \sqrt{\sin^2 \frac{\alpha_{\text{в}}}{2} + \cos^4 \frac{\alpha_{\text{в}}}{2}}

% 31. Длина криволинейного участка
l_{\text{кр}} = 2\rho \sin \frac{\alpha_{\text{в}}}{2}

% 32. Стрела изгиба
f_{\text{кр}} = \rho - \sqrt{\rho^2 - \frac{l_{\text{кр}}^2}{4}}

% 33. Проверка устойчивости в вертикальной плоскости
q_{\text{в}} \ge \frac{2 k_{\text{н.п}} S}{l_{\text{кр}} \sqrt{1 + \frac{1}{16} \left( \frac{l_{\text{кр}}}{f} \right)^2}}

% 34. Условие устойчивости в вертикальной плоскости
q_{\text{в}} \ge \frac{k_{\text{н.п}} S}{k_\alpha \rho}
