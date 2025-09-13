```jsx
import React from 'react';

const App = () => {
  return (
    <div className="min-h-screen bg-green-50 text-black">
      {/* Header */}
      <header className="bg-white border-b-4 border-green-600 py-4 px-6">
        <div className="max-w-7xl mx-auto flex items-center justify-between">
          <div className="flex items-center space-x-2">
            <div className="w-10 h-10 bg-green-600 rounded-xl flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" className="h-6 w-6 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
            </div>
            <h1 className="text-2xl font-bold text-green-700">RACER</h1>
          </div>
        </div>
      </header>

      {/* Hero Section */}
      <section className="py-20 px-6">
        <div className="max-w-4xl mx-auto text-center">
          <h2 className="text-4xl sm:text-6xl font-bold mb-6">
            Станьте курьером
            <span className="text-green-700"> уже сегодня!</span>
          </h2>
          <p className="text-xl text-gray-700 mb-12 max-w-3xl mx-auto">
            Работайте с гибким графиком, получайте ежедневные выплаты и зарабатывайте больше, чем вы думали!
          </p>

          <a 
            href="https://reg.eda.yandex.ru/?advertisement_campaign=forms_for_agents&user_invite_code=addd50b4bbf24cd3a4af2c708d6eeb94&utm_content=blank" 
            target="_blank" 
            rel="noopener noreferrer"
            className="inline-block bg-black text-white px-12 py-6 rounded-xl font-semibold text-2xl hover:bg-gray-800 transition-all transform hover:scale-105 shadow-lg"
          >
            СТАТЬ КУРЬЕРОМ
          </a>
        </div>
      </section>

      {/* Conditions Section */}
      <section className="py-16 px-6">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-12">
            <h2 className="text-3xl font-bold text-gray-800 mb-4">Условия работы</h2>
            <p className="text-lg text-gray-700 max-w-3xl mx-auto">
              Все условия для комфортной и выгодной работы курьером
            </p>
          </div>

          <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Быстрое подключение к сервису</h3>
              <p className="text-gray-700">Получите первый заказ сразу после регистрации</p>
            </div>

            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Ежедневные выплаты</h3>
              <p className="text-gray-700">Копите на свою мечту</p>
            </div>

            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Чаевые</h3>
              <p className="text-gray-700">Все чаевые от клиентов – ваши</p>
            </div>

            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Скидки на аренду транспорта</h3>
              <p className="text-gray-700">Выгодная скидка на аренду самокатов и велосипедов</p>
            </div>

            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Поддержка</h3>
              <p className="text-gray-700">Чаты для поддержки по самым разным вопросам</p>
            </div>

            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Обучение</h3>
              <p className="text-gray-700">Легко и просто объясним как складывать продукты, доставлять заказ и общаться с клиентами</p>
            </div>

            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Гибкий график</h3>
              <p className="text-gray-700">Доставляйте заказы в удобное для себя время</p>
            </div>

            <div className="bg-white p-8 rounded-2xl shadow-lg hover:shadow-xl transition-all duration-300">
              <h3 className="text-xl font-semibold text-gray-800 mb-3">Свободный выбор района</h3>
              <p className="text-gray-700">Выбирайте район, где хотите работать</p>
            </div>
          </div>
        </div>
      </section>

      {/* How It Works */}
      <section className="py-16 px-6 bg-green-100">
        <div className="max-w-7xl mx-auto">
          <div className="text-center mb-12">
            <h2 className="text-3xl font-bold text-gray-800 mb-4">Как стать курьером?</h2>
            <p className="text-lg text-gray-700 max-w-3xl mx-auto">
              Три простых шага, чтобы начать зарабатывать уже завтра
            </p>
          </div>

          <div className="grid grid-cols-1 md:grid-cols-3 gap-8">
            <div className="text-center p-8 bg-white rounded-2xl shadow-lg relative">
              <div className="absolute -top-4 -left-4 w-12 h-12 bg-black text-white rounded-full flex items-center justify-center text-2xl font-bold z-10">1</div>
              <div className="mt-12">
                <h3 className="text-xl font-semibold text-gray-800 mb-3">Заполните анкету</h3>
                <p className="text-gray-700">Займёт пару минут</p>
              </div>
            </div>

            <div className="text-center p-8 bg-white rounded-2xl shadow-lg relative">
              <div className="absolute -top-4 -left-4 w-12 h-12 bg-black text-white rounded-full flex items-center justify-center text-2xl font-bold z-10">2</div>
              <div className="mt-12">
                <h3 className="text-xl font-semibold text-gray-800 mb-3">Ознакомьтесь с правилами сотрудничества</h3>
              </div>
            </div>

            <div className="text-center p-8 bg-white rounded-2xl shadow-lg relative">
              <div className="absolute -top-4 -left-4 w-12 h-12 bg-black text-white rounded-full flex items-center justify-center text-2xl font-bold z-10">3</div>
              <div className="mt-12">
                <h3 className="text-xl font-semibold text-gray-800 mb-3">Выберите день для посещения курьерского центра и заберите термосумку</h3>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Final CTA Section */}
      <section className="py-16 px-6 bg-green-50">
        <div className="max-w-4xl mx-auto text-center">
          <h2 className="text-4xl font-bold text-gray-800 mb-6">
            Готовы начать зарабатывать?
          </h2>
          <p className="text-xl text-gray-700 mb-12 max-w-3xl mx-auto">
            Присоединяйтесь к тысячам курьеров, которые уже зарабатывают на своих мечтах!
          </p>
          
          <a 
            href="https://reg.eda.yandex.ru/?advertisement_campaign=forms_for_agents&user_invite_code=addd50b4bbf24cd3a4af2c708d6eeb94&utm_content=blank" 
            target="_blank" 
            rel="noopener noreferrer"
            className="inline-block bg-black text-white px-12 py-6 rounded-xl font-semibold text-2xl hover:bg-gray-800 transition-all transform hover:scale-105 shadow-lg"
          >
            СТАТЬ КУРЬЕРОМ
          </a>
        </div>
      </section>

      {/* Footer */}
      <footer className="py-12 px-6 bg-white border-t-4 border-green-600">
        <div className="max-w-7xl mx-auto text-center">
          <div className="flex items-center justify-center space-x-2 mb-4">
            <div className="w-8 h-8 bg-green-600 rounded-lg flex items-center justify-center">
              <svg xmlns="http://www.w3.org/2000/svg" className="h-5 w-5 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
              </svg>
            </div>
            <h3 className="text-xl font-bold text-green-700">RACER</h3>
          </div>
          <p className="text-gray-600 mb-6">
            Официальный партнер Яндекс Еды
          </p>
          <div className="border-t border-gray-200 pt-6 text-gray-500 text-sm">
            <p>&copy; 2024 RACER. Все права защищены.</p>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default App;
```
