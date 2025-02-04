<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Улучшенное генеалогическое дерево</title>
  <style>
    /* CSS-переменные для цветовой схемы */
    :root {
      --bg-color: #f4f4f4;
      --text-color: #333;
      --accent-blue: #007BFF;
      --father-bg: #a9cbb7;  /* мягкий зелёный */
      --mother-bg: #d8bfa9;  /* приглушённый золотой */
      --male-color: #00008b;
      --female-color: #8b0000;
      --hover-bg: #e0e0e0;
    }

    /* Сброс базовых стилей */
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 20px;
      font-family: Arial, sans-serif;
      background: var(--bg-color);
      color: var(--text-color);
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      text-align: center;
    }

    header {
      margin-bottom: 20px;
    }

    h1 {
      margin-bottom: 10px;
    }

    /* Строка поиска */
    #searchContainer {
      margin-bottom: 20px;
    }
    #searchInput {
      width: 300px;
      padding: 8px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }

    /* Адаптивное расположение деревьев */
    .tree-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: flex-start;
    }
    .tree, .center-node {
      margin-bottom: 20px;
    }
    .tree {
      width: 100%;
      max-width: 500px;
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: left;
    }
    .center-node {
      width: 100px;
      height: 100px;
      background: var(--accent-blue);
      color: #fff;
      font-size: 24px;
      font-weight: bold;
      border-radius: 50%;
      display: flex;
      justify-content: center;
      align-items: center;
      margin: auto;
    }

    /* Стили для списков */
    ul {
      list-style: none;
      padding-left: 20px;
      margin: 0;
    }
    li {
      margin: 8px 0;
      position: relative;
      cursor: pointer;
    }
    .node-label {
      display: inline-block;
      padding: 4px 8px;
      border-radius: 4px;
      transition: background 0.3s;
    }
    .node-label:hover {
      background: var(--hover-bg);
    }
    /* Анимация появления инфо-блока */
    .info {
      margin-left: 10px;
      font-size: 12px;
      opacity: 0;
      transform: translateX(10px);
      transition: opacity 0.5s, transform 0.5s;
    }
    .info.visible {
      opacity: 1;
      transform: translateX(0);
    }
    /* Анимация раскрытия/сжатия списков с keyframes */
    .child-list {
      margin-left: 20px;
      border-left: 2px dashed #ccc;
      padding-left: 10px;
      overflow: hidden;
      max-height: 0;
      transition: max-height 0.5s ease-out;
    }
    .child-list.expanded {
      max-height: 1000px;
      transition: max-height 0.7s ease-in;
    }
    /* Стрелки для элементов с потомками */
    .has-children > .node-label::after {
      content: " ▼";
      font-size: 12px;
    }
    .has-children.expanded > .node-label::after {
      content: " ▲";
    }
    /* Стилизация по семейным линиям */
    #fatherTree .child-person {
      background: var(--father-bg);
    }
    #motherTree .child-person {
      background: var(--mother-bg);
    }
    /* Гендерное выделение */
    .male { color: var(--male-color); }
    .female { color: var(--female-color); }

    /* Выделение совпадений при поиске */
    .highlight {
      background: yellow;
    }

    /* Скрытые элементы (поисковая фильтрация) */
    .hidden {
      display: none !important;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Генеалогическое дерево</h1>
      <!-- Поле поиска с комментариями -->
      <div id="searchContainer">
        <input type="text" id="searchInput" placeholder="Поиск по имени...">
      </div>
    </header>

    <main class="tree-container">
      <!-- Отцовская линия (семейство Исламклувых) -->
      <section class="tree" id="fatherTree" aria-label="Отцовская линия">
        <h2>Отцовская линия</h2>
        <ul>
          <!-- Дед со стороны отца -->
          <li>
            <span class="node-label"><strong>Исламкул Жумагулов</strong> (1954)</span>
          </li>
          <!-- Бабуля со стороны отца -->
          <li>
            <span class="node-label"><strong>Асранкулова Мактымай</strong> (1954)</span>
          </li>
          <!-- Гульбарчын с мужем Султан -->
          <li class="has-children">
            <span class="node-label child-person female" data-year="1977">
              <strong>Жумагулова Гульбарчын Исламкуловна</strong> (1977)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Муж: Султан (1977)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person male" data-year="2007">
                      <strong>Даниэль Жумагулов</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2009">
                      <strong>Артур Жумагулов</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <!-- Шайырбек с женой Сютой -->
          <li class="has-children">
            <span class="node-label child-person male" data-year="1979">
              <strong>Жумагулов Шайырбек Исламкулович</strong> (1979)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Жена: Сюта (1979)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person male" data-year="2004">
                      <strong>Исламкул Амангелди Шайырбекович</strong> (Это я)
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2007">
                      <strong>Исламкулов Алихан Шайырбекович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2011">
                      <strong>Исламкулова Раяна Шайырбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <!-- Садыр с женой Жамильей -->
          <li class="has-children">
            <span class="node-label child-person male" data-year="1981">
              <strong>Жумагулов Садыр Исламкулович</strong> (1981)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Жена: Жамиля (1985)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person female" data-year="2011">
                      <strong>Исламкулова Асема Садырбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2014">
                      <strong>Исламкулов Нурдолот Садырбекович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <!-- Назар с женой Матаевой Салтанат -->
          <li class="has-children">
            <span class="node-label child-person male" data-year="1986">
              <strong>Жумагулов Назар Исламкулович</strong> (1986)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Жена: Матаева Салтанат (1986)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person male" data-year="2009">
                      <strong>Исламкулов Атахан Назарбекович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2010">
                      <strong>Исламкулова Айжан Назарбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2013">
                      <strong>Исламкулова Аружан Назарбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <!-- Жазгуль с мужем Нурланом -->
          <li class="has-children">
            <span class="node-label child-person female" data-year="1988">
              <strong>Жумагулова Жазгуль Исламкуловна</strong> (1988)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Муж: Нурлан (1986)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person female" data-year="2009">
                      <strong>Тургунова Зулайка Нурланбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2013">
                      <strong>Тургунов Эламан Нурланбекович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2015">
                      <strong>Тургунова Айлин Нурланбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2018">
                      <strong>Тургунова Алсу Нурланбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
        </ul>
      </section>

      <!-- Центральный узел "Я" -->
      <aside class="center-node" aria-label="Я">
        Я
      </aside>

      <!-- Материнская линия (семейство Орунбаевых) -->
      <section class="tree" id="motherTree" aria-label="Материнская линия">
        <h2>Материнская линия</h2>
        <ul>
          <!-- Дед со стороны матери -->
          <li>
            <span class="node-label"><strong>Уринбой Пазилович</strong> (1954; погиб в 1988)</span>
          </li>
          <!-- Бабуля со стороны матери -->
          <li>
            <span class="node-label"><strong>Акбермерт Орозбаева</strong> (1954)</span>
          </li>
          <!-- Сюта с детьми -->
          <li class="has-children">
            <span class="node-label child-person female" data-year="1979">
              <strong>Пазилова Сюта Орунбаевна</strong> (1979)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Муж: Жумагулов Шайырбек Исламкулович (1979)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person male">
                      <strong>Исламкул Амангелди Шайырбекович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male">
                      <strong>Исламкулов Алихан Шайырбекович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female">
                      <strong>Исламкулова Раяна Шайырбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <!-- Арапбай (Азиз) -->
          <li class="has-children">
            <span class="node-label child-person female" data-year="1981">
              <strong>Пазилова Арапбай (Азиз) Орунбаевна</strong> (1981)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Жена: ГУКУ</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети (от второй жены, Нуржамал Орунбаева):</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person female" data-year="2003">
                      <strong>Сумая Арабаевна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2005">
                      <strong>Муслима Арабаевна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2007">
                      <strong>Аяна Арабаевна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <!-- Жылдыз -->
          <li class="has-children">
            <span class="node-label child-person female" data-year="1984">
              <strong>Пазилова Жылдыз Орунбаевна</strong> (1984)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Муж: Исмаил Исламов (1981)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person female" data-year="2007">
                      <strong>Исламова Мадина Исмаиловна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2009">
                      <strong>Исламова Айзат Исмаиловна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2009">
                      <strong>Исламов Бекзат Исмаилович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2014">
                      <strong>Исламов Умар Исмаилович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2016">
                      <strong>Исламов Амир Исламович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2018">
                      <strong>Исламова Сезим Исмаиловна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
          <!-- Ильгиз -->
          <li class="has-children">
            <span class="node-label child-person female" data-year="1986">
              <strong>Пазилова Ильгиз Орунбаевна</strong> (1986)
            </span>
            <ul class="child-list">
              <li>
                <span class="node-label">Жена: Чынар Дуйшева (1988)</span>
              </li>
              <li class="has-children">
                <span class="node-label">Дети:</span>
                <ul class="child-list">
                  <li>
                    <span class="node-label child-person female" data-year="2009">
                      <strong>Орунбаева Хадижа Ильгизбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2011">
                      <strong>Орунбаева Асема Ильгизбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2014">
                      <strong>Орунбаева Севьде Ильгизбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person female" data-year="2018">
                      <strong>Орунбаева Айлин Ильгизбековна</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                  <li>
                    <span class="node-label child-person male" data-year="2022">
                      <strong>Орунбаев Чынгыз Ильгизбекович</strong>
                      <span class="info"></span>
                    </span>
                  </li>
                </ul>
              </li>
            </ul>
          </li>
        </ul>
      </section>
    </main>
  </div>

  <script>
    /* ===============================================
       Делегирование событий для раскрытия/сжатия узлов
    =============================================== */
    document.addEventListener('click', (e) => {
      // Проверяем, если клик был по элементу с классом .node-label внутри li.has-children
      const label = e.target.closest('.has-children > .node-label');
      if (label) {
        e.stopPropagation();
        const parentLi = label.parentElement;
        const childList = parentLi.querySelector('.child-list');
        if (childList) {
          childList.classList.toggle('expanded');
          parentLi.classList.toggle('expanded');
        }
      }
    });

    /* ===============================================
       Расчёт возраста и статуса (школьник/студент)
    =============================================== */
    (() => {
      const currentYear = 2025; // Фиксированный текущий год
      document.querySelectorAll('.child-person').forEach(el => {
        const birthYear = parseInt(el.getAttribute('data-year'));
        if (!isNaN(birthYear)) {
          const age = currentYear - birthYear;
          let infoText = "";
          // Если возраст меньше 18 – школьник, иначе студент
          if (age < 18) {
            const grade = age - 5; // примерный расчет класса
            infoText = `(${age} лет, примерно ${grade}-й класс)`;
          } else {
            infoText = `(${age} лет, студент)`;
          }
          const infoEl = el.querySelector('.info');
          if (infoEl) {
            infoEl.textContent = infoText;
            setTimeout(() => infoEl.classList.add('visible'), 100);
          }
        }
      });
    })();

    /* ===============================================
       Поиск по имени с выделением и дебаунсингом
    =============================================== */
    const debounce = (fn, delay) => {
      let timeoutId;
      return (...args) => {
        clearTimeout(timeoutId);
        timeoutId = setTimeout(() => fn.apply(this, args), delay);
      };
    };

    const highlightText = (element, query) => {
      // Восстанавливаем исходный текст
      const original = element.textContent;
      if (!query) return original;
      const regex = new RegExp(`(${query})`, 'gi');
      return original.replace(regex, '<span class="highlight">$1</span>');
    };

    const searchHandler = () => {
      const filter = document.getElementById('searchInput').value.trim().toLowerCase();
      // Проходим по всем узлам с текстом
      document.querySelectorAll('.node-label').forEach(label => {
        const text = label.textContent.toLowerCase();
        const li = label.parentElement;
        if (text.includes(filter)) {
          li.classList.remove('hidden');
          // Подсвечиваем совпадения
          label.innerHTML = highlightText(label.textContent, filter);
          // Раскрываем все родительские списки, чтобы отобразить найденный элемент
          let parent = li.parentElement;
          while (parent && parent.classList.contains('child-list')) {
            parent.classList.add('expanded');
            parent = parent.parentElement;
          }
        } else {
          li.classList.add('hidden');
          // Если строка поиска пуста, сбрасываем подсветку
          if (!filter) label.innerHTML = label.textContent;
        }
      });
    };

    document.getElementById('searchInput')
      .addEventListener('input', debounce(searchHandler, 300));
  </script>
</body>
</html>
