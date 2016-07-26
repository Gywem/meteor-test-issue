# meteor-test-issue

## How to reproduce

Install npm dependencies,

`npm install`

execute tests,

`npm test`

and it gets the issue:

``` javascript
=> Errors prevented startup:                  

   While processing files with templating (for target web.browser):
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/createOnBlur.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/createOnChange.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/createOnDragStart.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/createOnDrop.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/createOnFocus.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/getValue.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/isEvent.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/silenceEvent.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/events/__tests__/silenceEvents.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/actions.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/asyncValidation.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/bindActionData.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/createReduxForm.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/fieldValue.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/getDisplayName.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/getValues.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/getValuesFromState.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/handleSubmit.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/initializeState.spec.js.html:1: Can't set DOCTYPE here.  (Meteor
   sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/isPristine.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/isValid.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/mapValues.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/read.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/readField.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/readFields.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/reducer.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/removeField.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/resetState.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/setErrors.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/updateField.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/wrapMapDispatchToProps.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/wrapMapStateToProps.spec.js.html:1: Can't set DOCTYPE here.
   (Meteor sets <!DOCTYPE html> for you)
   node_modules/redux-form/coverage/lcov-report/src/__tests__/write.spec.js.html:1: Can't set DOCTYPE here.  (Meteor sets
   <!DOCTYPE html> for you)

=> Your application has errors. Waiting for file change.
```
