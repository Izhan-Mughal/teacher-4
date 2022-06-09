<template>
  <div>
    <div class="search-main  px-3  pt-1 pb-4 ">
      <div class="
          d-lg-flex d-md-block d-block
          text-lg-start text-center
          mx-2
          my-3
          justify-content-between
          align-items-center
        ">
        <p class="mb-0 fw-bolder text-blue mb-2 mb-lg-0 fs-5">Search Breakout Game</p>
        <button class="btn-p fw-bolder p-lg-1 p-2">Explore All</button>
      </div>
      <div class="px-0 search py-3 row mx-0">
        <div class="col-12 col-lg-7 col-md-7 d-flex">
          <div class="input-div">
            <input type="search" class="w-100 px-4" id="search-input" placeholder="Search All Games..." />
            <span class="search-icon px-4 py-1">
              <i class="fas fa-search text-light"></i>
            </span>
          </div>
        </div>
        <div class="col-12 col-lg-5 col-md-5 mt-lg-0 mt-md-0 mt-3">
          <div class="drop-div d-flex d-lg-flex d-md-block justify-content-evenly align-items-center">
            <b-dropdown text="Grade">
              <div class="row">
                <div class="col-lg-6 col-12">
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">Pre-Kindergarten
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">Kindergarten
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">1st Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">2nd Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">3rd Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">4th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">5th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">6th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>

                </div>
                <div class="col-lg-6 col-12">
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">7th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">8th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">9th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">10th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">11th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">12th Grade
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>
                  <b-dropdown-item class="text-white fw-bold" href="#">
                    <label class="container1">Adult
                      <input type="checkbox">
                      <span class="checkmark">
                      </span>
                    </label>
                  </b-dropdown-item>

                </div>
              </div>
            </b-dropdown>
            <div class="Another_Menu">

              <b-dropdown text="Subject">
                <div class="row">
                  <div class="col-lg-6 col-12">
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Math
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                      <div class="bg-white1">
                        <b-dropdown-item class="text-green2 Hello1 fw-bold" href="#">
                          <label class="container1">Algebra
                            <input type="checkbox">
                            <span class="checkmark">
                            </span>
                          </label>
                        </b-dropdown-item>
                        <b-dropdown-item class="text-green2 fw-bold" href="#">
                          <label class="container1">Foundational Math
                            <input type="checkbox">
                            <span class="checkmark">
                            </span>
                          </label>
                        </b-dropdown-item>
                        <b-dropdown-item class="text-green2 fw-bold" href="#">
                          <label class="container1">User Generated Math
                            <input type="checkbox">
                            <span class="checkmark">
                            </span>
                          </label>
                        </b-dropdown-item>
                        <b-dropdown-item class="text-green2 fw-bold" href="#">
                          <label class="container1">Pre-Algebra
                            <input type="checkbox">
                            <span class="checkmark">
                            </span>
                          </label>
                        </b-dropdown-item>
                        <b-dropdown-item class="text-green2 fw-bold" href="#">
                          <label class="container1">Geometry
                            <input type="checkbox">
                            <span class="checkmark">
                            </span>
                          </label>
                        </b-dropdown-item>

                      </div>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Science
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Social Studies
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Language
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Elementary
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Team Development
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                  </div>
                  <div class="col-lg-6 col-12">
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Library
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">The Arts
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Holiday/Seasonal
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Lack of the Day
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Computer Science
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
                    <b-dropdown-item class="text-white fw-bold" href="#">
                      <label class="container1">Career Technical Education
                        <input type="checkbox">
                        <span class="checkmark">
                        </span>
                      </label>
                    </b-dropdown-item>
 
  
                  </div>
                </div>
              </b-dropdown>
            </div>
          <div class="Another_Menu2">
            <b-dropdown text="Type">
              <b-dropdown-item class="text-green2 fw-bold" href="#">
                <label class="container1">Digital
                  <input type="checkbox">
                  <span class="checkmark">
                  </span>
                </label>
              </b-dropdown-item>
              <b-dropdown-item class="text-green2 fw-bold" href="#">
                <label class="container1">Kit
                  <input type="checkbox">
                  <span class="checkmark">
                  </span>
                </label>
              </b-dropdown-item>
              <b-dropdown-item class="text-green2 fw-bold" href="#">
                <label class="container1">All
                  <input type="checkbox">
                  <span class="checkmark">
                  </span>
                </label>
              </b-dropdown-item>
            </b-dropdown>
          </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>