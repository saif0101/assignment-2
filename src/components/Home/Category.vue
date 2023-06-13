<style>
/*start faq question */

.faq-container .question .faq-plus-icon {
  display: none;
}
.faq-container .question.active .faq-plus-icon {
  display: block;
}
.faq-container .question .faq-minus-icon {
  display: block;
}
.faq-container .question.active .faq-minus-icon {
  display: none;
}

/*end faq question */

.activeTab {
  border-bottom: 2px solid #001844;
  font-weight: 700;
}
</style>

<template class="">
  <div class="custome-container font-openSans py-20">
    <div class="">
      <!-- Tabs -->
      <ul id="tabs" class="flex  pt-2 px-1 w-full overflow-x-auto">
        <li
          class="border-b-2 border-[#6D6E70]/20 text-lg text-[#001844] px-5 py-3"
        >
          <a class="whitespace-nowrap" id="default-tab" href="#first">A-Z:All</a>
        </li>
        <li
          class="border-b-2 border-[#6D6E70]/20 text-lg text-[#001844] px-5 py-3"
        >
          <a class="whitespace-nowrap" href="#second">Therapeutic Area: All</a>
        </li>
        <li
          class="border-b-2 border-[#6D6E70]/20 text-lg text-[#001844] px-5 py-3"
        >
          <a class="whitespace-nowrap" href="#third">Commonly Prescribed</a>
        </li>
      </ul>

      <!-- Tab Contents -->
      <div id="tab-contents">
        <div id="first" class="p-4">
          <div class="faq-container space-y-5 mt-5">
            <!-- faq one -->
            <div class="">
              <div class="question bg-ash cursor-pointer px-6 py-4">
                <div class="flex  lg:items-center gap-5">
                  <h4
                    class="text-[26px] leading-[30px] md:text-[40px] md:leading-[60px] lg:text-[56px] lg:leading-[72px] text-light text-[#001844]"
                  >
                    Cancer
                  </h4>

                  <div>
                    <img
                      class="faq-minus-icon inline-block"
                      :src="PlusButton"
                      alt="icon"
                    />

                    <img
                      class="faq-plus-icon inline-block"
                      :src="MinusButton"
                      alt="icon"
                    />
                  </div>
                </div>
              </div>
              <div class="answer px-6">
                <div class="border-b-2 border-[#6D6E70]/30 w-fit pb-5">
                  <figure>
                    <img
                      class="w-fit"
                      src="https://besnik-space.fra1.cdn.digitaloceanspaces.com/ezytor/theme/Fms2nAiOwUndCrSNwbt11686389811.webp"
                      alt="Herceptin"
                    />
                  </figure>

                  <figcaption class="mt-2">
                    <p
                      class="text-[20px] leading-[27px] font-semibold text-[#001844]"
                    >
                      Herceptin
                    </p>
                    <a class="underline text-[#001844]" href="" target="_blank"
                      >Prescribing information</a
                    >

                    <div class="flex items-center gap-2 mt-5">
                      <a
                        class="text-[16px] leading-[20px] font-bold underline"
                        href=""
                        >view more</a
                      >
                      <svg
                        width="18"
                        height="16"
                        viewBox="0 0 18 16"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          d="M10 15L17 8L10 0.999999M17 8L1 8"
                          stroke="#0F1A43"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </svg>
                    </div>
                  </figcaption>
                </div>
              </div>
            </div>

            <!-- faq two -->
            <div class="">
              <div class="question bg-ash cursor-pointer px-6 py-4">
                <div class="flex lg:items-center gap-5">
                  <h4
                    class="text-[26px] leading-[30px] md:text-[40px] md:leading-[60px] lg:text-[56px] lg:leading-[72px] text-light text-[#001844]"
                  >
                  Cardiovascular
                  </h4>

                  <div>
                    <img
                      class="faq-minus-icon inline-block"
                      :src="PlusButton"
                      alt="icon"
                    />

                    <img
                      class="faq-plus-icon inline-block"
                      :src="MinusButton"
                      alt="icon"
                    />
                  </div>
                </div>
              </div>
              <div class="answer px-6">
                <div class="border-b-2 border-[#6D6E70]/30 w-fit pb-5">
                  <figure>
                    <img
                      class="w-fit"
                      src="https://besnik-space.fra1.cdn.digitaloceanspaces.com/ezytor/theme/Fms2nAiOwUndCrSNwbt11686389811.webp"
                      alt="Herceptin"
                    />
                  </figure>

                  <figcaption class="mt-2">
                    <p
                      class="text-[20px] leading-[27px] font-semibold text-[#001844]"
                    >
                      Herceptin
                    </p>
                    <a class="underline text-[#001844]" href="" target="_blank"
                      >Prescribing information</a
                    >

                    <div class="flex items-center gap-2 mt-5">
                      <a
                        class="text-[16px] leading-[20px] font-bold underline"
                        href=""
                        >view more</a
                      >
                      <svg
                        width="18"
                        height="16"
                        viewBox="0 0 18 16"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          d="M10 15L17 8L10 0.999999M17 8L1 8"
                          stroke="#0F1A43"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </svg>
                    </div>
                  </figcaption>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div id="second" class="hidden p-4">

            <div class="faq-container space-y-5 mt-5">
            <!-- faq one -->
            <div class="">
              <div class="question bg-ash cursor-pointer px-6 py-4">
                <div class="flex lg:items-center gap-5">
                  <h4
                    class="text-[26px] leading-[30px] md:text-[40px] md:leading-[60px] lg:text-[56px] lg:leading-[72px] text-light text-[#001844]"
                  >
                    Cancer
                  </h4>

                  <div>
                    <img
                      class="faq-minus-icon inline-block"
                      :src="PlusButton"
                      alt="icon"
                    />

                    <img
                      class="faq-plus-icon inline-block"
                      :src="MinusButton"
                      alt="icon"
                    />
                  </div>
                </div>
              </div>
              <div class="answer px-6">
                <div class="border-b-2 border-[#6D6E70]/30 w-fit pb-5">
                  <figure>
                    <img
                      class="w-fit"
                      src="https://besnik-space.fra1.cdn.digitaloceanspaces.com/ezytor/theme/Fms2nAiOwUndCrSNwbt11686389811.webp"
                      alt="Herceptin"
                    />
                  </figure>

                  <figcaption class="mt-2">
                    <p
                      class="text-[20px] leading-[27px] font-semibold text-[#001844]"
                    >
                      Herceptin
                    </p>
                    <a class="underline text-[#001844]" href="" target="_blank"
                      >Prescribing information</a
                    >

                    <div class="flex items-center gap-2 mt-5">
                      <a
                        class="text-[16px] leading-[20px] font-bold underline"
                        href=""
                        >view more</a
                      >
                      <svg
                        width="18"
                        height="16"
                        viewBox="0 0 18 16"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          d="M10 15L17 8L10 0.999999M17 8L1 8"
                          stroke="#0F1A43"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </svg>
                    </div>
                  </figcaption>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div id="third" class="hidden p-4">
            <div class="faq-container space-y-5 mt-5">
        
            <!-- faq two -->
            <div class="">
              <div class="question bg-ash cursor-pointer px-6 py-4">
                <div class="flex lg:items-center gap-5">
                  <h4
                    class="text-[26px] leading-[30px] md:text-[40px] md:leading-[60px] lg:text-[56px] lg:leading-[72px] text-light text-[#001844]"
                  >
                  Cardiovascular
                  </h4>

                  <div>
                    <img
                      class="faq-minus-icon inline-block"
                      :src="PlusButton"
                      alt="icon"
                    />

                    <img
                      class="faq-plus-icon inline-block"
                      :src="MinusButton"
                      alt="icon"
                    />
                  </div>
                </div>
              </div>
              <div class="answer px-6">
                <div class="border-b-2 border-[#6D6E70]/30 w-fit pb-5">
                  <figure>
                    <img
                      class="w-fit"
                      src="https://besnik-space.fra1.cdn.digitaloceanspaces.com/ezytor/theme/Fms2nAiOwUndCrSNwbt11686389811.webp"
                      alt="Herceptin"
                    />
                  </figure>

                  <figcaption class="mt-2">
                    <p
                      class="text-[20px] leading-[27px] font-semibold text-[#001844]"
                    >
                      Herceptin
                    </p>
                    <a class="underline text-[#001844]" href="" target="_blank"
                      >Prescribing information</a
                    >

                    <div class="flex items-center gap-2 mt-5">
                      <a
                        class="text-[16px] leading-[20px] font-bold underline"
                        href=""
                        >view more</a
                      >
                      <svg
                        width="18"
                        height="16"
                        viewBox="0 0 18 16"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          d="M10 15L17 8L10 0.999999M17 8L1 8"
                          stroke="#0F1A43"
                          stroke-width="2"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        />
                      </svg>
                    </div>
                  </figcaption>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";
import PlusButton from "../../assets/Plus@1x.png"
import MinusButton from "../../assets/mius@1x.png"

const tabTogglers = ref([]);
const tabContents = ref([]);

const toggleTab = (index) => {
  for (let i = 0; i < tabTogglers.value.length; i++) {
    if (i === index) {
      tabTogglers.value[i].parentElement.classList.add("activeTab");
      tabContents.value[i].classList.remove("hidden");
    } else {
      tabTogglers.value[i].parentElement.classList.remove("activeTab");
      tabContents.value[i].classList.add("hidden");
    }
  }
};

onMounted(() => {
  const tabsContainer = document.querySelector("#tabs");
  tabTogglers.value = tabsContainer.querySelectorAll("#tabs a");
  tabContents.value = document.querySelectorAll("#tab-contents > div");

  tabTogglers.value.forEach((toggler, index) => {
    toggler.addEventListener("click", (e) => {
      e.preventDefault();
      toggleTab(index);
    });
  });

  // Set the first tab as active by default
  toggleTab(0);

  //   for faq

  (function () {
    /**
     * hide FAQ's all answers without clicked question's answer
     * @param questions
     * @param avoidableIndex
     * @param faqAnswerControlBy
     */
    function hideOthersAnswer(questions, avoidableIndex, faqAnswerControlBy) {
      questions.forEach((question, i) => {
        if (i !== avoidableIndex) {
          let answerArea = selectAnswerForToggle(question);

          if (faqAnswerControlBy === "style") {
            answerArea.style.height = "0px";
          }

          answerArea?.classList.remove("active");
          question?.classList.remove("active");
        }
      });
    }

    /**
     * select answer element of clicked question. Answer may place inside question element or after question element.
     * @param question
     * @returns {null|Element|*}
     */
    function selectAnswerForToggle(question) {
      let answerFromInside = question.querySelector(".answer");
      if (answerFromInside) {
        return answerFromInside;
      }

      let answerFromNextElement = question.nextElementSibling;
      if (answerFromNextElement && answerFromNextElement.matches(".answer")) {
        return answerFromNextElement;
      }

      return null;
    }

    /** select all faq container **/
    let faqContainers = document.querySelectorAll(".faq-container");

    if (faqContainers.length) {
      let defaultFaqOptions = {
        slide_speed: 300, // expected value  numeric miliseconds
        close_others: true, // expected value 'true', 'false'
        answer_control_by: "style", // expected value 'class', 'style'
      };

      faqContainers.forEach((faqContainer) => {
        let faqAnswerSlideSpeed = faqContainer.hasAttribute("slide_speed")
          ? parseInt(faqContainer.getAttribute("slide_speed"))
          : defaultFaqOptions.slide_speed;

        let faqCloseOtherAnswer = faqContainer.hasAttribute("close_others")
          ? faqContainer.getAttribute("close_others") == "true"
          : defaultFaqOptions.close_others;

        let faqAnswerControlBy = faqContainer.hasAttribute("answer_control_by")
          ? faqContainer.getAttribute("answer_control_by")
          : defaultFaqOptions.answer_control_by;

        let questions = faqContainer.querySelectorAll(".question");

        questions.forEach((question, i) => {
          let answerArea = selectAnswerForToggle(question);

          let answerAreaHeight = answerArea.getBoundingClientRect().height;

          /**
           * add some style for slide-up & down transition when answerControlBy value is 'style' (default).
           */
          if (faqAnswerControlBy === "style") {
            answerArea.style.cssText = `
                    overflow: hidden;
                    transition: height ${faqAnswerSlideSpeed}ms ease-in;
                  `;
            answerArea.style.height = "0px";
          }

          question.addEventListener("click", function () {
            answerArea.classList.toggle("active");
            question.classList.toggle("active");

            if (faqAnswerControlBy === "style") {
              if (answerArea.style.height === "0px") {
                answerArea.style.height = answerAreaHeight + "px";
              } else {
                answerArea.style.height = "0px";
              }
            }

            if (faqCloseOtherAnswer) {
              hideOthersAnswer(questions, i, faqAnswerControlBy);
            }
          });
        });
      });
    }
  })();
});
</script>
