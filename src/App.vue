<template>
  <div class="container">
    <header>
      <div class="profile-header">
        <img src="./assets/images/ProfilePicture.webp" alt="Profile Picture" class="header-profile-picture">
        <div class="header-text">
          <h1 class="centered-name">Кристина Петрова</h1>
          <div class="title-wrapper">
            <div class="line"></div>
            <p class="title">Начинающий тестировщик</p>
            <div class="line"></div>
          </div>
        </div>
      </div>
      <div class="decoration">
        <div class="circle accent"></div>
        <div class="circle"></div>
        <div class="circle accent"></div>
      </div>
    </header>

    <main>
      <section class="block" style="--delay: 0s">
        <h2>
    <span class="icon-wrapper">
      <ContactIcon />
    </span>
          Контакты
        </h2>
        <div class="contacts-grid">
          <div class="contact-item">
            <div class="contact-icon">
              <ContactPhoneIcon />
            </div>
            <div>
              <div class="contact-label">Телефон</div>
              <a href="tel:+79155466909" class="contact-value">+7 (915) 546-6909</a>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">
              <ContactMailIcon />
            </div>
            <div>
              <div class="contact-label">Email</div>
              <a href="mailto:kristina.petroffa.2612@yandex.ru" class="contact-value">kristina.petroffa.2612@yandex.ru</a>
            </div>
          </div>

          <div class="contact-item">
            <div class="contact-icon">
              <ContactLocationIcon />
            </div>
            <div>
              <div class="contact-label">Местоположение</div>
              <div class="contact-value">Воронеж, Россия</div>
            </div>
          </div>
        </div>
      </section>

      <section class="block" style="--delay: 0.2s">
        <h2>
          <span class="icon-wrapper">
            <BriefcaseIcon/>
          </span>
          Опыт проекта
        </h2>
        <div>
          <p><span class="project-name">Fintrack</span> — сервис для учёта личных финансов. Занималась ручным
            тестированием: проверяла бизнес-логику, вёрстку, интерфейс, формы, фильтры, экспорт данных. Писала
            чек-листы, тест-кейсы, баг-репорты, вела задачи в Jira.</p>
        </div>
      </section>

      <section class="block" style="--delay: 0.3s">
        <h2>
          <span class="icon-wrapper">
            <SkillsIcon/>
          </span>
          Навыки
        </h2>
        <div class="skills-grid">
          <span>Ручное тестирование</span>
          <span>Тест-кейсы и баг-репорты</span>
          <span>Chrome DevTools</span>
          <span>Postman</span>
          <span>SQL</span>
          <span>REST API</span>
          <span>Jira</span>
          <span>Confluence</span>
          <span>Agile/Scrum</span>
          <span>Git</span>
        </div>
      </section>

      <section class="block" style="--delay: 0.4s">
        <h2>
          <span class="icon-wrapper">
            <EducationIcon/>
          </span>
          Образование
        </h2>
        <div>
          <p><strong>Воронежский государственный университет</strong>, 2025<br/>Факультет компьютерных наук,
            Информационная безопасность</p>
        </div>
      </section>

      <section class="block" style="--delay: 0.5s">
        <h2>
          <span class="icon-wrapper">
            <GlobeIcon/>
          </span>
          Языки
        </h2>
        <div>
          <ul>
            <li>Русский — родной</li>
            <li>Английский — B2 (средне-продвинутый)</li>
          </ul>
        </div>
      </section>
    </main>

    <footer>
      <div class="wave"></div>
      <p>© 2025 Кристина Петрова</p>
      <div class="contacts-mini">
        <a href="tel:+79155466909">
          <PhoneIcon/>
        </a>
        <a href="mailto:kristina.petroffa.2612@yandex.ru">
          <MailIcon/>
        </a>
        <a href="#">
          <LocationIcon/>
        </a>
      </div>
    </footer>
  </div>
</template>

<script>
import ContactIcon from "./assets/icons/ContactIcon.vue";
import UserIcon from "./assets/icons/UserIcon.vue";
import BriefcaseIcon from "./assets/icons/BriefcaseIcon.vue";
import SkillsIcon from "./assets/icons/SkillsIcon.vue";
import EducationIcon from "./assets/icons/EducationIcon.vue";
import GlobeIcon from "./assets/icons/GlobeIcon.vue";
import PhoneIcon from "./assets/icons/PhoneIcon.vue";
import MailIcon from "./assets/icons/MailIcon.vue";
import LocationIcon from "./assets/icons/LocationIcon.vue";
import ContactPhoneIcon from "./assets/icons/ContactPhoneIcon.vue";
import ContactMailIcon from "./assets/icons/ContactMailIcon.vue";
import ContactLocationIcon from "./assets/icons/ContactLocationIcon.vue";

export default {
  name: 'App',
  components: {
    ContactIcon,
    UserIcon,
    BriefcaseIcon,
    SkillsIcon,
    EducationIcon,
    GlobeIcon,
    PhoneIcon,
    MailIcon,
    LocationIcon,
    ContactPhoneIcon,
    ContactMailIcon,
    ContactLocationIcon,
  }
}
</script>