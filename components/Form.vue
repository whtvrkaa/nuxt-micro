<template>
  <div
    class="wrap px-8 mx-auto mt-12 sm:px-6 md:px-4 lg:px-2 xl:px-0 xl:prose-xl lg:prose-lg md:prose-md pb-12"
    style="margin-top: 6rem; max-width: 70ch"
  >
    <h2 class="pb-2">
      Do you have a new idea with a solution you would like to share with us ?
    </h2>
    <p>
      If you have a new idea with a solution to help enhance what we do, or how
      we do things, please complete the form below.
    </p>

    <div
      class="grid mt-8 justify-items-center shadow-md flex-shrink md:flex-shrink-0"
    >
      <div class="">
        <div class="p-8">
          <!--alert message-->
          <div
            class="shadow-lg mt-3 pt-3 pb-3 w-full text-white text-center hover:bg-indigo-400 rounded-full cursor-pointer hidden"
          ></div>

          <form action="https://submit-form.com/70NjSVaW">
            <input
              type="hidden"
              name="_redirect"
              value="http://localhost:52498/thankyou"
            />
            <!-- Username -->
            <div style="display: flex; gap: 2rem">
              <div style="width: 50%">
                <label for="first_name" class="text-md">First Name</label>
                <input
                  id="first_name"
                  class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-gray-700 pb-1"
                  type="text"
                  placeholder=""
                />
              </div>
              <div style="width: 50%">
                <label for="surname" class="text-md">Surname</label>
                <input
                  id="surname"
                  class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-gray-700 pb-1"
                  type="text"
                  placeholder=""
                />
              </div>
            </div>
            <!-- Title -->
            <div class="pb-5">
              <label id="title" class="text-md">Title</label>
              <select
                class="bg-transparent w-full py-1.5 px-3 text-gray-800 border border-gray-500 transition duration-500 focus:outline-none focus:border-black rounded"
              >
                <option value=""></option>
                <option value="Dame">Dame</option>
                <option value="Doctor">Doctor</option>
                <option value="Lady">Lady</option>
                <option value="Lord">Lord</option>
                <option value="Miss">Miss</option>
                <option value="Mr">Mr</option>
                <option value="Mrs">Mrs</option>
                <option value="Ms">Ms</option>
                <option value="Mx">Mx</option>
                <option value="Prof">Prof</option>
                <option value="Sir">Sir</option>
              </select>
            </div>
            <!-- Company Name -->
            <div>
              <label id="company_name" class="text-md">Company Name</label>
              <input
                id="company_name"
                name="company_name"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Company Website -->
            <div>
              <label id="company_website" class="text-md"
                >Company Website</label
              >
              <input
                id="company_website"
                name="company_website"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Company Size -->
            <div>
              <label id="company_size" class="text-md">Company Size</label>
              <input
                id="company_size"
                name="company_size"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- State/County -->
            <div>
              <label id="state_county" class="text-md">State/County * </label>
              <input
                id="state_county"
                name="state_county"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Country-->
            <div>
              <label id="country" class="text-md">Country * </label>
              <input
                id="country"
                name="country"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Phone Number -->
            <div>
              <label id="phone_number" class="text-md">Phone Number</label>
              <input
                id="phone_number"
                name="phone_number"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Email Address -->
            <div>
              <label id="email" class="text-md">Email Address *</label>
              <input
                id="email"
                name="email"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="email"
                placeholder=""
              />
            </div>
            <!-- Idea Category -->
            <div class="pb-5">
              <label id="idea_category" class="text-md"
                >Select one category that best fits your idea *</label
              >
              <select
                class="bg-transparent w-full py-1.5 px-3 text-gray-800 border border-gray-500 transition duration-500 focus:outline-none focus:border-black rounded"
              >
                <option value=""></option>
                <option
                  value="New products (merchandise) or manufacturing and production"
                >
                  New products (merchandise) or manufacturing and production
                </option>
                <option value="Improving a specific business area">
                  Improving a specific business area
                </option>
                <option value="Improving our internal business services">
                  Improving our internal business services
                </option>
                <option value="Making a difference to our colleagues">
                  Making a difference to our colleagues
                </option>
                <option value="Making a difference to our communities">
                  Making a difference to our communities
                </option>
                <option value="Making a difference to our customers">
                  Making a difference to our customers
                </option>
                <option value="Making our business simpler">
                  Making our business simpler
                </option>
              </select>
            </div>
            <!-- Describe your idea -->
            <div>
              <label id="idea_desc" class="text-md"
                >Please describe your idea in a headline *</label
              >
              <br />
              <span>max 70 characters</span>
              <input
                id="idea_desc"
                name="idea_desc"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Describe what problem your idea solves -->
            <div>
              <label id="idea_desc" class="text-md"
                >Please describe what problem your idea solves for Boots and/or
                its customers *</label
              >
              <br /><span>max 300 words</span>
              <textarea
                id="idea_desc"
                name="idea_desc"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Summary of your idea -->
            <div>
              <label id="idea_desc" class="text-md"
                >Please provide a short summary of your idea *</label
              >
              <br /><span>max 300 words</span>
              <textarea
                id="idea_desc"
                name="idea_desc"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <!-- Summary of your idea -->

            <div
              class="pb-5 umbraco-forms-field isyourproductorideaalreadyinthemarket singlechoice mandatory alternating"
            >
              <label
                for="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8"
                class="umbraco-forms-label"
              >
                Is your product or idea already in the market?
                <span class="umbraco-forms-indicator">*</span>
              </label>

              <div class="umbraco-forms-field-wrapper">
                <div
                  class="radiobuttonlist"
                  id="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8"
                >
                  <input
                    type="radio"
                    name="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8"
                    id="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8_0"
                    value="Yes"
                    data-val="true"
                    data-rule-required="true"
                    data-msg-required="Select whether your product/idea is already in the market"
                  />
                  <label for="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8_0"
                    >Yes</label
                  >
                  <br />
                  <input
                    type="radio"
                    name="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8"
                    id="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8_1"
                    value="No"
                    data-val="true"
                    data-rule-required="true"
                    data-msg-required="Select whether your product/idea is already in the market"
                  />
                  <label for="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8_1">No</label>
                  <br />
                </div>

                <span
                  class="field-validation-valid"
                  data-valmsg-for="5e26a8b8-b067-4cc6-8dcf-6aafa90525e8"
                  data-valmsg-replace="true"
                ></span>
              </div>
            </div>
            <!-- Summary of your idea -->
            <div>
              <label id="idea_desc" class="text-md"
                >Do you have existing or prior contacts in Boots? If yes please
                state whom</label
              >
              <br /><span>max 300 words</span>
              <textarea
                id="idea_desc"
                name="idea_desc"
                class="bg-transparent border m-auto block border-gray-500 w-full mb-6 text-grey-700 pb-1"
                type="text"
                placeholder=""
              />
            </div>
            <div
              class="pb-5 umbraco-forms-field doesyourideaholdanyrelevanttechnicalaccreditations singlechoice mandatory"
            >
              <label
                for="340e07e5-c807-4d11-d7a4-a60a973b2812"
                class="umbraco-forms-label"
              >
                Does your idea hold any relevant technical accreditations?
                <span class="umbraco-forms-indicator">*</span>
              </label>

              <div class="umbraco-forms-field-wrapper">
                <div
                  class="radiobuttonlist"
                  id="340e07e5-c807-4d11-d7a4-a60a973b2812"
                >
                  <input
                    type="radio"
                    name="340e07e5-c807-4d11-d7a4-a60a973b2812"
                    id="340e07e5-c807-4d11-d7a4-a60a973b2812_0"
                    value="Yes"
                    data-val="true"
                    data-rule-required="true"
                    data-msg-required="Please provide a value for Does your idea hold any relevant technical accreditations?"
                  />
                  <label for="340e07e5-c807-4d11-d7a4-a60a973b2812_0"
                    >Yes</label
                  >
                  <br />
                  <input
                    type="radio"
                    name="340e07e5-c807-4d11-d7a4-a60a973b2812"
                    id="340e07e5-c807-4d11-d7a4-a60a973b2812_1"
                    value="No"
                    data-val="true"
                    data-rule-required="true"
                    data-msg-required="Please provide a value for Does your idea hold any relevant technical accreditations?"
                  />
                  <label for="340e07e5-c807-4d11-d7a4-a60a973b2812_1">No</label>
                  <br />
                </div>

                <span
                  class="field-validation-valid"
                  data-valmsg-for="340e07e5-c807-4d11-d7a4-a60a973b2812"
                  data-valmsg-replace="true"
                ></span>
              </div>
            </div>

            <div
              class="umbraco-forms-field isyourideapatentedorthesubjectofapendingpublishedpatentapplication singlechoice mandatory"
            >
              <label
                for="eaec8f6c-6374-4a47-ca79-b99d9ca07879"
                class="umbraco-forms-label"
              >
                Is your idea patented or the subject of a pending published
                patent application?
                <span class="umbraco-forms-indicator">*</span>
              </label>

              <div class="umbraco-forms-field-wrapper">
                <div
                  class="radiobuttonlist"
                  id="eaec8f6c-6374-4a47-ca79-b99d9ca07879"
                >
                  <input
                    type="radio"
                    name="eaec8f6c-6374-4a47-ca79-b99d9ca07879"
                    id="eaec8f6c-6374-4a47-ca79-b99d9ca07879_0"
                    value="Yes"
                    data-val="true"
                    data-rule-required="true"
                    data-msg-required="Please provide a value for Is your idea patented or the subject of a pending published patent application?"
                  />
                  <label for="eaec8f6c-6374-4a47-ca79-b99d9ca07879_0"
                    >Yes</label
                  >
                  <br />
                  <input
                    type="radio"
                    name="eaec8f6c-6374-4a47-ca79-b99d9ca07879"
                    id="eaec8f6c-6374-4a47-ca79-b99d9ca07879_1"
                    value="No"
                    data-val="true"
                    data-rule-required="true"
                    data-msg-required="Please provide a value for Is your idea patented or the subject of a pending published patent application?"
                  />
                  <label for="eaec8f6c-6374-4a47-ca79-b99d9ca07879_1">No</label>
                  <br />
                </div>

                <span
                  class="field-validation-valid"
                  data-valmsg-for="eaec8f6c-6374-4a47-ca79-b99d9ca07879"
                  data-valmsg-replace="true"
                ></span>
              </div>
            </div>
            <fieldset
              class="umbraco-forms-fieldset"
              id="09d82219-1fd4-4a55-b80e-0199ce6d1915"
            >
              <div class="row-fluid">
                <div class="umbraco-forms-container col-md-12">
                  <div
                    class="umbraco-forms-field termsandconditions titleanddescription alternating"
                  >
                    <div class="umbraco-forms-field-wrapper">
                      <div id="5d62dee8-9d8a-41ef-fcf8-4fc04dffe552" class="">
                        <h2>Terms and Conditions</h2>
                        <p>
                          Please make sure you read our terms and conditions
                          because you’re agreeing to them by submitting
                          information to Boots. It’s also worth reading our
                          <a
                            href="https://www.tescoplc.com/services/privacy-cookies-policy/"
                            >privacy and cookies policy</a
                          >
                          so you understand how we collect and use your personal
                          data. Then if you’re happy, complete the form below
                          and we’ll be in touch.<br />
                          <br />
                          You acknowledge that: <br />
                          <br />
                          (a) you are not an employee of Boots;
                          <br />
                          (b) you are not submitting any confidential
                          information as part of this submission; and <br />
                          (c) you have reviewed and agree to the
                          <a href="/terms-and-conditions/"
                            >terms and conditions</a
                          >.
                        </p>
                      </div>

                      <span
                        class="field-validation-valid"
                        data-valmsg-for="5d62dee8-9d8a-41ef-fcf8-4fc04dffe552"
                        data-valmsg-replace="true"
                      ></span>
                    </div>
                  </div>
                  <div
                    class="pb-5 umbraco-forms-field doyouaccepttheaboveterms dataconsent mandatory"
                  >
                    <label
                      for="8cee66a3-6643-4e8d-822d-d5f08dcef98a"
                      class="umbraco-forms-label"
                    >
                      Do you accept the above terms?
                      <span class="umbraco-forms-indicator">*</span>
                    </label>

                    <div class="umbraco-forms-field-wrapper">
                      <div
                        class="radiobuttonlist dataconsent"
                        id="8cee66a3-6643-4e8d-822d-d5f08dcef98a"
                      >
                        <input
                          type="radio"
                          name="8cee66a3-6643-4e8d-822d-d5f08dcef98a"
                          id="yes"
                          value="accepted"
                          data-val="true"
                          data-val-requiredlist="You must accept the terms and conditions to submit your idea"
                        />
                        <label for="yes">Yes</label>
                        <br />

                        <input
                          type="radio"
                          name="8cee66a3-6643-4e8d-822d-d5f08dcef98a"
                          id="no"
                          value="declined"
                          data-val="true"
                          data-val-requiredlist="You must accept the terms and conditions to submit your idea"
                        />
                        <label for="yes">No</label>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </fieldset>
            <input
              class="submit-btn shadow-lg mt-3 text-white rounded-full cursor-pointer"
              type="submit"
              value="Submit"
            />
          </form>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.submit-btn {
  background-color: #004990;
  width: 8rem;
  padding-top: 0.3rem;
  padding-bottom: 0.3rem;
}
.submit-btn:hover {
  opacity: 0.9;
}
span {
  color: #666;
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}
.radio {
  position: absolute;
  top: 0;
  left: 0;
  height: 2.5rem;
  width: 2.5rem;
  background: #c9ded6;
  border-radius: 50%;
}
.radio::after {
  display: block;
  content: '';
  position: absolute;
  opacity: 0;
  top: 0.5rem;
  left: 0.5rem;
  width: 1.5rem;
  height: 1.5rem;
  border-radius: 50%;
  background: #fff;
  transition: opacity 0s 0.75s;
}
</style>
