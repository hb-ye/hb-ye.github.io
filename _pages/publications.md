---
layout: archive
#title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### Selected Publications
(including **errata**, **source code** and **author accepted manuscripts**)

- Xiao, Z., **Ye, H.**, Chung, E., 2025. New formulations and solution approaches for train eco-driving problems. <u>Transportation Research Part B</u> 195, 103210. [[Author Accepted Manuscript](/files/2025Xiao_AAM.pdf)][[Presentation](/files/2025Xiao_Presentation.pdf)]
- Wu, F., **Ye, H.**, Bektas, T., Dong, M., 2025. New and tractable formulations for the eco-driving and the eco-routing-and-driving problems. <u>European Journal of Operational Research</u> 321 (2), 445-461.
- **Ye, H.**, 2022. On stochastic-user-equilibrium-based day-to-day dynamics. <u>Transportation Science</u> 56 (1), 103–117. [[Author Accepted Manuscript](/files/2022_SUE-DTD_TS_AAM.pdf)]
- Wu, F., Bektaş, T., Dong, M., **Ye, H.**, Zhang, D., 2021. Optimal driving for vehicle fuel economy under traffic speed uncertainty. <u>Transportation Research Part B</u> 154, 175-206. [[Presentation](/files/2021Wu_Presentation.pdf)]
- **Ye, H.**, Xiao, F., Yang, H., 2021. Day-to-day dynamics with advanced traveler information. <u>Transportation Research Part B</u> 144, 23-44. [[Author Accepted Manuscript](/files/2021YXY_AAM.pdf)]
- **Ye, H.**, Xiao, F., Yang, H., 2018. Exploration of day-to-day route choice models by a virtual experiment. <u>Transportation Research Part C</u> 94, 220-235, and <u>ISTTT22</u> (poster), Illinois, USA, 2017.
- **Ye, H.**, Yang, H., 2017. Rational behavior adjustment process with boundedly rational user equilibrium. <u>Transportation Science</u> 51 (3), 968-980. 
- **Ye, H.**, Liu, R., 2017. Nonlinear programming methods based on closed-form expressions for optimal train control. <u>Transportation Research Part C</u> 82, 102-123. [[Codes of Case Studies](/files/2017YL_codes.zip)]
- **Ye, H.**, Liu, R., 2016. A multiphase optimal control method for multi-train control and scheduling on railway lines. <u>Transportation Research Part B</u> 93, 377-393. [[Codes of Case Studies](/files/2016YL_codes.zip)]
- Xiao, F., Yang, H., **Ye, H.**, 2016. Physics of day-to-day network flow dynamics. <u>Transportation Research Part B</u> 86, 86-103. [[Errata](/files/2016XYY_Errata.pdf)]
- **Ye, H.**, Yang, H., Tan, Z.J., 2015. Learning marginal-cost pricing via a trial-and-error procedure with day-to-day flow dynamics. <u>Transportation Research Part B</u> 81, 794-807, and <u>ISTTT21</u> (lectern), Japan, 2015. 
- <strong>Ye, H.</strong>, Yang, H., 2013. Continuous price and flow dynamics of tradable mobility credits. <u>Transportation Research Part B</u> 57, 436-450, and <u>ISTTT20</u> (lectern), The Netherlands, 2013.
