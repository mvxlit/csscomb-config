.csscomb.json with css grid 

Соблюдайте определенный порядок стилей для удобства и читаемости кода:

1. Свойства позиционирования
2. Блочной модели, 
3. Шрифты. 
4. Прочее оформление
5. Анимации


.element {
  /* Позиционирование */
  position: relative;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;

  /* Блочная модель */
  display: flex;
  align-items: center;
  margin: 10px;
  padding: 10px 20px;
  border: 1px solid red;
  width: 200px;
  height: 100px;
  box-sizing: border-box;

  /* Типографика */
  font-family: Arial;
  font-size: 25px;
  font-style: italic;
  text-decoration: none;
  color: red;

  /* Оформление */
  background: red;
  opacity: 1;

  /* Анимации */
  transform: translateX(5px);
  animation: shake 0.3s infinite;
}
