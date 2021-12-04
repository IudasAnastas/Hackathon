<template>
    <div class="Mwrapper">
        <div style="display: inline-block;width:20%;float:left">
            <div style="font-family: gilroy-reguar;" class="BigColor">Наш проект и команда</div>
            <br><br>
            <div class="SmColor"><a>Наименование проекта</a></div>
            <div class="SmColor"><a>Цели и задачи</a></div>
            <div class="SmColor"><a>Тип проекта</a></div>
            <div class="SmColor"><a>Обязательные мероприятия</a></div>
            <div class="SmColor"><a>План работы и контрольные точки</a></div>
            <div class="SmColor"><a>Результаты проета</a></div>
            <div class="SmColor"><a>Организационная структура</a></div>
            <div class="SmColor"><a>Карта коммуникаций</a></div>
            <div class="SmColor"><a>Команда</a></div>
        </div>
        <div style="display: inline-block;padding-left:100px">
              <div style="font-family: gilroy-reguar;" class="header">Разработка программного решения для онбординга новых IT-специалистов банка</div>
             <div style="font-family: gilroy-reguar;" class="text">
                 <p><strong>Цель:</strong></p>
                <ul>    
                <li>Сокращение срока адаптации нового сотрудника проекта с 3 месяцев до 1 месяца.</li><br>
                </ul>

                <p><strong>Задачи: </strong></p>

                <ul>
                <li>Выявить пользовательские проблемы</li>
                <li>Определить цель</li>
                <li>Создать прототип </li>
                <li>Провести тестирование</li>
                <li>Провести ретроспективу</li>
                </ul>
                <br>
                <p><strong>Тип проекта: </strong></p>
                
                <ul>
                <li>Agile, Scrum</li>
                </ul>
                <br>
                <p><strong>Обязательные мероприятия: </strong></p>

                <ul>
                <li>Длительность спринта - 2 недели. Конец спринта - четверг. </li>
                <li>Обзор спринта (1 раз в спринт, ЧТ). Основная задача обзора спринта — получить обратную связь по реализованному функционалу</li>
                <li>Ретроспектива (1 раз в спринт, ЧТ). Анализ предыдущего спринта с целью выявить проблемы и найти их решения, а также закрепить процессы, которые хорошо сработали.</li>
                <li>Планирование (1 раз в спринт, ЧТ)</li>
                <li>Уточнение Бэклога Продукта (груминг) (1 раз в 2 спринта)</li>
                <li>Daily. Проводится ежедневно, кроме пятницы. Проводим в zoom</li>
                </ul>
                <br>
                <p><strong>План работ и контрольные точки </strong></p>

                <ul>
                <li>Этап 1. Проектирование. Результат - интерактивный прототип адаптации ИТ-специалистов согласован с владельцем процесса. Срок окончания - 01.01.2022 года. </li>
                <li>Этап 2. Разработка. Результат - интерактивный прототип адаптации ИТ-специалистов разработан и выгружен на тестовую площадку. Срок окончания - 01.02.2022 года. </li>
                <li>Этап 3. Тестирование и отладка. Результат - интерактивный прототип адаптации ИТ-специалистов работает согласно протоколу тестирования. Отладочные работы выполнены. Срок окончания - 01.03.2022 года. </li>
                <li>Этап 4. Внедрение. Результат - интерактивный прототип адаптации ИТ-специалистов запущен для всех специалистов Банка. Срок окончания - 01.04.2022 года. </li>
                </ul>
                <br>
                <p><strong>Результаты проекта:</strong></p>

                <ul>
                <li>Веб-приложение для сотрудников банка. </li>
                </ul>

                <p><strong>Организационная структура проекта </strong></p>

                <ul>
                <li>Руководитель проекта </li>
                <li>Технический руководитель проекта </li>
                <li>Администратор проекта </li>
                <li>Команда разработки и тестирования (2 проектировщика, 6 разработчиков PHP, 1 разработчик SAP PO, 1 разработчик SAP HR, 2 тестировщика)</li>
                <li>Команда внедрения (1 технолог, 1 релиз-менеджер)</li>
                <li>Команда сопровождения (2 сотрудника 2-й линии поддержки)</li>
                </ul>

                <p><strong>Карта коммуникаций (по RACI) </strong></p>

                <p><strong>Условные обозначения</strong></p>

                <p><strong>Роль: </strong></p>

                <ul>
                <li>РП - руководитель проекта</li>
                <li>ТРП - технический руководитель проекта</li>
                <li>РЦ - руководители подразделений разработки</li>
                <li>ВП - владелец продукта</li>
                <li>ВПр - владельцы процессов</li>
                <li>TL - Руководитель группы разработки (Team Lead)</li>
                <li>DP - Дизайнер продукта (Product Designer)</li>
                <li>D - Раработчик (Developer)</li>
                <li>T - Тестировщик (Tester)</li>
                <li>DevOps - Специалист по релизам</li>
                </ul>
                <br>
                <p><strong>Зона ответственности: </strong></p>

                <ul>
                <li>R – Responsible (исполняет);</li>
                <li>A – Accountable (несет ответственность);</li>
                <li>C – Consult before doing (консультирует до исполнения);</li>
                <li>I – Inform after doing (оповещается после исполнения).</li>
                </ul>

                <p> </p>
             </div>
               <div class="table">
          <img :src="require('@/assets/img/table.svg')">
          </div>
          <div style="font-family: gilroy-reguar;" class="BigColor">Команда</div>
        </div>
       

    </div>
</template>

<script>
    

    export default {
        components: {
          
        },
        data:()=>({
            usrs:[
                {
                    Name:"Чернова Эльмира Артемовна",
                    Job:"Руководитель группы разработки (Team Lead)",
                    Group:"",
                    Phone1:"(71) 3729",
                    Phone2:"+(903) 676-8494",
                    Email:"PrimerPrimer@gmail.com",
                    Adr:"Москва, Бербеневская Набережная, д 7",
                },
                {
                    Name:"Кудрявцев Даниил Русланович",
                    Job:"Владелец процессов",
                    Group:"",
                    Phone1:"(71) 3729",
                    Phone2:"+(903) 676-8494",
                    Email:"PrimerPrimer@gmail.com",
                    Adr:"Москва, Бербеневская Набережная, д 7",
                },
                {
                    Name:"Кудрявцев Даниил Русланович",
                    Job:"Владелец процессов",
                    Group:"Группа внутренних коммункаций и развития корпоративной культуры",
                    Phone1:"(71) 3729",
                    Phone2:"+(903) 676-8494",
                    Email:"PrimerPrimer@gmail.com",
                    Adr:"Москва, Бербеневская Набережная, д7",
                },
            ]
        }),
        name: "Connections"
    }
</script>

<style scoped>
    .BigColor {
        font-family: Gilroy;
        font-style: normal;
        font-weight: 600;
        font-size: 28px;
        line-height: 33px;
        letter-spacing: 0.015em;
        color: #EA5719;
    }
    a{
        color: #6E7ABA;
        font-family: Gilroy;
        font-style: normal;
        text-decoration: none;
        font-size:20px;
    }
    .SmColor {
        text-decoration: underline;
        margin-bottom: 20px;
        color: #292b61;
        font-family: gilroy-regular;
        font-size: 16px;
        font-size: 20px;
        line-height: 23px;
        letter-spacing: 0.015em;
        text-decoration-line: underline;
    }
    .header{
        font-family: Gilroy;
        font-style: normal;
        font-weight: 600;
        font-size: 28px;
        line-height: 33px;
        text-align: center;
        letter-spacing: 0.015em;
        max-width: 921px;
        color: #EA5719;
    }

    .Mwrapper {
        padding-top: 30px;
        padding-left: 200px;
        padding-right: 200px;
        margin-bottom:200px;
        font-family: gilroy-regular!important;
        height: 200000px;
    }
        .table{
        position: absolute;
        width: 921px;
        height: 3374px;
        left: 618px;
        top: 2027px;
    }

    .text{
        font-family: Gilroy;
        font-style: normal;
        width: 980px;
        height: 1570px;
        font-weight: 600;
        font-size: 20px;
        line-height: 24px;
        letter-spacing: 0.015em;

        /* Акцент1 */

        color: #34398E;
    }
</style>