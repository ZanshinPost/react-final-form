# React Form Library Comparison

PRs to this page are highly encouraged, _especially_ by the authors of other
form libraries. If you feel that your library is misrepresented (or not included
and you'd like it to be), please correct the mistake.

| Feature                               |               [🏁 React-Final-Form](https://github.com/erikras/react-final-form#-react-final-form)                | [Formik](https://github.com/jaredpalmer/formik)  |  [Redux-Form](https://github.com/erikras/redux-form)  |
| ------------------------------------- | :---------------------------------------------------------------------------------------------------------------: | :----------------------------------------------: | :---------------------------------------------------: |
| Bundle Size                           | [3.5k](https://bundlephobia.com/result?p=final-form) + [2.2k](https://bundlephobia.com/result?p=react-final-form) | [7.5k](https://bundlephobia.com/result?p=formik) | [26.8k](https://bundlephobia.com/result?p=redux-form) |
| Works without Redux                   |                                                        ✅                                                         |                        ✅                        |                          ❌                           |
| Record-Level Sync Validation          |                                                        ✅                                                         |                        ✅                        |                          ✅                           |
| Record-Level Async Validation         |                                                        ✅                                                         |                        ✅                        |                          ✅                           |
| Field-Level Sync Validation           |                                                        ✅                                                         |                        ✅                        |                          ✅                           |
| Field Level Async Validation          |                                                        ✅                                                         |                        ✅                         |                          ✅                           |
| Render Prop for Form                  |                                                        ✅                                                         |                        ✅                        |                          ❌                           |
| Render Prop for Field                 |                                                        ✅                                                         |                        ✅                        |                          ❌                           |
| Avoids unnecessary form rerenders     |                                                        ✅                                                         |          ❌ <sup>[1](#footnote1)</sup>           |                          ✅                           |
| Higher Order Component           |                                           ❌ <sup>[2](#footnote2)</sup>                                           |                        ✅                      |                            ✅                         |
| Render Prop Component           |                                           ✅                                            |                        ✅                      |                            ❌                         |
| Access to form data from outside form |                                                        ❌                                                         |                        ❌                        |                          ✅                           |
| Awesome Optical Illusion Logo         |                                                        ❌                                                         |                        ✅                        |                          ❌                           |

---

<a name="footnote1">1</a>: This is not really an issue on all but the most
enormous forms.

<a name="footnote3">2</a>: See [Why no HOC?](faq.md#why-no-hoc)
