<template>
  <div :class="$style.wrapper">
    <div :class="$style.content">
      <div :class="$style.profile">
        <section :class="$style.header">
          <div :class="$style.avatar">
            <div :class="$style.avatarImg">
              <img src="@/assets/img/avatar.jpg" alt="" />
            </div>
          </div>
          <h1 :class="$style.name">Alina Ishchenko</h1>
          <p :class="$style.title">Frontend Developer</p>
        </section>
        <section :class="$style.block">
          <div :class="$style.contact">
            <div :class="$style.contactIcon">
              <img src="@/assets/img/icons/location.svg" alt="Location" />
            </div>
            <span>Belarus, Brest</span>
          </div>
          <div :class="$style.contact">
            <div :class="$style.contactIcon">
              <img src="@/assets/img/icons/phone.png" alt="Phone" />
            </div>
            <span>+375 (44) 543-01-90</span>
          </div>
          <div :class="$style.contact">
            <div :class="$style.contactIcon">
              <img src="@/assets/img/icons/email.svg" alt="Email" />
            </div>
            <a href="">aloha.nearby@gmail.com</a>
          </div>
          <div :class="$style.contact">
            <div :class="$style.contactIcon">
              <img src="@/assets/img/icons/telegram.svg" alt="Telegram" />
            </div>
            <a href="" target="_blank">Telegram</a>
          </div>
          <div :class="$style.contact">
            <div :class="$style.contactIcon">
              <img src="@/assets/img/icons/github.svg" alt="GitHub" />
            </div>
            <a href="https://github.com/Alcon-dev" target="_blank">GitHub</a>
          </div>
          <div :class="$style.contact">
            <div :class="$style.contactIcon">
              <img src="@/assets/img/icons/linkedin.svg" alt="LinkedIn" />
            </div>
            <a href="" target="_blank">LinkedIn</a>
          </div>
        </section>
      </div>
      <div :class="$style.main">
        <section :class="$style.block">
          <h2 :class="$style.blockTitle">About me</h2>
          <div :class="$style.blockText">
            <p>
              Frontend Developer with commercial experience in building websites, web applications,
              and Telegram Mini Apps. I focus on creating modern user interfaces - from responsive
              layouts based on design systems to client-side logic and API integration. I worked on
              real freelance projects, covering the full frontend development cycle - product
              launch, support, and further development. I confidently work with technical
              documentation, learn quickly, can adapt to the team's and product's tech stack, and am
              interested in professional growth and development within the company.
            </p>
          </div>
        </section>
        <section :class="$style.block">
          <h2 :class="$style.blockTitle">Work Experience</h2>
          <div :class="$style.experiences">
            <div :class="$style.experience">
              <div :class="$style.experienceHeader">
                <div :class="$style.experienceGroup">
                  <div :class="$style.companyIcon">
                    <img src="@/assets/img/icons/st-logo.svg" alt="" />
                  </div>
                  <div :class="$style.experienceInfo">
                    <h3 :class="$style.company">Smith Team</h3>
                    <p :class="$style.position">Frontend Developer</p>
                  </div>
                </div>
                <span :class="$style.date">2024 - 2026</span>
              </div>
              <ul :class="$style.description">
                <li>Development of websites, web applications, and Telegram Mini Apps</li>
                <li>Full-cycle SPA development: from layout to client-side logic</li>
                <li>API integration and working with data</li>
                <li>Running the backend locally for development and testing</li>
                <li>Working with Figma designs and technical documentation</li>
                <li>Improving performance and user experience</li>
              </ul>
            </div>
            <div :class="$style.experience">
              <div :class="$style.experienceHeader">
                <div :class="$style.experienceGroup">
                  <div :class="$style.companyIcon">
                    <img src="@/assets/img/icons/alutech-icon.svg" alt="" />
                  </div>
                  <div :class="$style.experienceInfo">
                    <h3 :class="$style.company">Alutech</h3>
                    <p :class="$style.position">Accountant</p>
                  </div>
                </div>
                <span :class="$style.date">2022 — 2024</span>
              </div>
              <ul :class="$style.description">
                <li>Preparation of financial and management reports</li>
                <li>Creating shipping and accompanying documents</li>
                <li>Preparing invoices, including CMR documents</li>
                <li>Checking the accuracy of primary documents</li>
                <li>Data analysis and verification of figures</li>
                <li>Working according to regulations and meeting deadlines and requirements</li>
              </ul>
              <p :class="$style.note">
                This experience helped me develop a high level of responsibility, analytical
                thinking, and attention to detail - skills that I directly use in frontend
                development.
              </p>
            </div>
          </div>
        </section>
        <section :class="$style.block">
          <h2 :class="$style.blockTitle">Hard Skills</h2>
          <ul :class="$style.skills">
            <li>JavaScript (ES6+)</li>
            <li>Vue.js / Vue 3</li>
            <li>SPA</li>
            <li>HTML5 / CSS3</li>
            <li>SCSS / SASS</li>
            <li>Responsive Design</li>
            <li>REST API integration</li>
            <li>Git / GitHub</li>
            <li>Webpack / Vite</li>
            <li>Figma</li>
            <li>Testing & Debugging</li>
            <li>Working with application state</li>
          </ul>
        </section>
        <section :class="$style.block">
          <h2 :class="$style.blockTitle">Soft Skills</h2>
          <ul :class="$style.skills">
            <li>Critical thinking</li>
            <li>Attention to detail</li>
            <li>Good communication skills</li>
            <li>Fast learner</li>
            <li>Responsibility</li>
          </ul>
        </section>
        <section :class="$style.block">
          <h2 :class="$style.blockTitle">Languages</h2>
          <ul :class="$style.languages">
            <li>English — B1</li>
            <li>Russian — C2</li>
            <li>Belarusian — Native</li>
          </ul>
        </section>
        <section :class="$style.block">
          <h2 :class="$style.blockTitle">Education</h2>
          <div :class="$style.education">
            <div :class="$style.educationHeader">
              <div :class="$style.educationGroup">
                <div :class="$style.educationIcon">
                  <img src="@/assets/img/icons/bseu.svg" alt="" />
                </div>
                <div :class="$style.experienceInfo">
                  <p :class="$style.company">Belarusian State Economic University</p>
                  <p :class="$style.position">Accounting and Economics Faculty</p>
                </div>
              </div>
              <span :class="$style.date">2018 — 2022</span>
            </div>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Resume'
}
</script>

<style module lang="scss">
.wrapper {
  max-width: 62.5rem;
  margin: 0 auto;
  background: white;
  border-radius: 0.75rem;
  box-shadow: 0 0.25rem 1.25rem rgba(0, 0, 0, 0.1);
  overflow: hidden;
}
.content {
  display: grid;
  grid-template-columns: 18.75rem 1fr;
  gap: 0;
}
.profile {
  background: $bg-light;
  padding: 2rem 1.5rem;
  border-right: 0.0625rem solid $border-color;
}
.main {
  padding: 2rem 2.5rem;
}
.header {
  text-align: center;
  margin-bottom: 2.5rem;
  padding-bottom: 2rem;
  border-bottom: 0.0625rem solid $border-color;
}
.avatar {
  display: flex;
  justify-content: center;
  margin-bottom: 1.5rem;
}
.avatarImg {
  width: 7.5rem;
  height: 7.5rem;
  border-radius: 50%;
  background: white;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 2.5rem;
  font-weight: 600;
  color: $purple;
  border: 0.25rem solid white;
  box-shadow: 0 0.125rem 0.625rem rgba(0, 0, 0, 0.1);
  overflow: hidden;
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%;
  }
}
.name {
  font-size: 1.8rem;
  margin: 0 0 0.5rem 0;
  font-weight: 700;
  color: $text-primary;
}
.title {
  font-size: 1rem;
  margin: 0;
  color: $text-secondary;
  font-weight: 400;
}
.block {
  margin-bottom: 2.5rem;
  &:last-child {
    margin-bottom: 0;
  }
}
.blockTitle {
  font-size: 0.95rem;
  color: $purple;
  margin: 0 0 1rem 0;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 0.05em;
}
.blockText {
  font-size: 0.95rem;
  line-height: 1.7;
  color: $text-primary;
  margin: 0;
}
.contact {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  margin-bottom: 1rem;
  font-size: 0.9rem;
  color: $text-primary;
  &:last-child {
    margin-bottom: 0;
  }
  a {
    color: $text-primary;
    text-decoration: none;
    transition: all ease 0.35s;
    &:hover {
      color: $purple;
    }
  }
}
.contactIcon {
  width: 2rem;
  height: 2rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  background: white;
  border-radius: 50%;
  box-shadow: 0 0.0625rem 0.1875rem rgba(0, 0, 0, 0.1);
  svg {
    width: 1.25rem;
    height: 1.25rem;
  }
  img {
    width: 1.25rem;
    height: 1.25rem;
    object-fit: contain;
  }
}
.experiences {
  display: flex;
  flex-direction: column;
  gap: 2rem;
}
.experience {
  padding: 1.5rem;
  background: $bg-light;
  border-radius: 0.5rem;
  border-left: 0.1875rem solid $purple;
}
.experienceHeader {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1rem;
  gap: 1rem;
}
.experienceGroup {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  flex: 1;
}
.experienceInfo {
  display: flex;
  flex-direction: column;
  gap: 0.25rem;
}
.companyIcon {
  width: 2.5rem;
  height: 2.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  background: white;
  border-radius: 50%;
  box-shadow: 0 0.0625rem 0.1875rem rgba(0, 0, 0, 0.1);
  overflow: hidden;
  position: relative;
  svg {
    width: 1.25rem;
    height: 1.25rem;
  }
  img {
    width: 1.5rem;
    height: 1.5rem;
    object-fit: contain;
    object-position: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
}
.company {
  font-size: 1rem;
  color: $text-primary;
  margin: 0;
  font-weight: 600;
}
.position {
  font-size: 0.9rem;
  color: $text-secondary;
  margin: 0;
  font-weight: 400;
}
.date {
  color: $text-secondary;
  font-size: 0.9rem;
  font-weight: 400;
  white-space: nowrap;
}
.description {
  list-style: none;
  padding: 0;
  margin: 0 0 1rem 0;
  li {
    padding: 0.4rem 0;
    color: $text-primary;
    font-size: 0.9rem;
    line-height: 1.6;
    padding-left: 1rem;
    position: relative;
    &:before {
      content: '•';
      position: absolute;
      left: 0;
      color: $text-primary;
    }
  }
}
.note {
  margin: 1rem 0 0 0;
  padding: 1rem;
  background: rgba(155, 126, 217, 0.05);
  border-radius: 0.25rem;
  font-size: 0.9rem;
  line-height: 1.6;
  color: $text-primary;
  font-style: italic;
}
.skills {
  list-style: none;
  padding: 0;
  margin: 0;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 0.5rem 1rem;
  li {
    padding: 0.4rem 0;
    color: $text-primary;
    font-size: 0.9rem;
    position: relative;
    padding-left: 1rem;
    &:before {
      content: '•';
      position: absolute;
      left: 0;
      color: $text-primary;
    }
  }
}
.languages {
  list-style: none;
  padding: 0;
  margin: 0;
  li {
    padding: 0.4rem 0;
    color: $text-primary;
    font-size: 0.9rem;
    position: relative;
    padding-left: 1rem;
    &:before {
      content: '•';
      position: absolute;
      left: 0;
      color: $text-primary;
    }
  }
}
.education {
  padding: 1.5rem;
  background: $bg-light;
  border-radius: 0.5rem;
  border-left: 0.1875rem solid $purple;
}
.educationHeader {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 1rem;
}
.educationGroup {
  display: flex;
  align-items: center;
  gap: 0.75rem;
  flex: 1;
}
.educationIcon {
  width: 2.5rem;
  height: 2.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-shrink: 0;
  background: white;
  border-radius: 50%;
  box-shadow: 0 0.0625rem 0.1875rem rgba(0, 0, 0, 0.1);
  overflow: hidden;
  position: relative;
  img {
    width: 2rem;
    height: 2rem;
    object-fit: contain;
    object-position: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }
}
@media (max-width: 60.5rem) {
  .content {
    grid-template-columns: 1fr;
  }
  .profile {
    border-right: none;
    border-bottom: 0.0625rem solid $border-color;
  }
  .avatarImg {
    width: 6.25rem;
    height: 6.25rem;
    font-size: 2rem;
  }
  .name {
    font-size: 1.6rem;
  }
}
@media (max-width: 48rem) {
  .wrapper {
    padding: 1rem 0.5rem;
    border-radius: 0.5rem;
  }
  .profile,
  .main {
    padding: 1.5rem;
  }
  .block {
    margin-bottom: 2rem;
  }
  .header {
    margin-bottom: 2rem;
    padding-bottom: 1.5rem;
  }
  .skills {
    grid-template-columns: repeat(2, 1fr);
  }
}
</style>
