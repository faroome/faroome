### Hi there 👋
#Программа позволяет высчитать к-во орков на фронт
#Запрос к-ва орков в штуках
ork = int(input("Сколько орков штук ? "))
#Запрос расстояния фронта
zona = int(input("расстояние фронта в км ? "))
#Выводим контрольные суммы
print ("орков", ork)
print ("фронт", zona)
#Просчитываем орков на километр фронта
ork_km = (ork/zona)
#Выводим данные
print ("Орков на км", {round(ork_km)})
#Просчитываем расстояние в метрах между орками
ork_dis = (1000/ork_km)
#Выводим расстояние между орками в метрах
print ("расстояние между орками в метрах", {round(ork_dis)})

nex = ("расстояние между орками в метрах", {round(ork_dis)})
print (nex)
<!--
**faroome/faroome** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
