# Salesforce-Admin

## 
- Locale setting
Define how data, time, address, currency, name and number fields are desplayed
  - Company wide locale set(e.g. date/money)
    - Setup
      - Setting
        - Company Settings
          - Company information
  - Personal setting
    - Setup
      - My personal Information
        - Language & Time Zone
- language setting
  Translation workbench???
  - Fully-access(all SF features)
    - Only this can be selection for the default organization language or user display language.
    - The following two must be selected and can not be deactivated
  - end users(all standard object **field labels and pages**, not setup and help)
  - Platform only(customizations and standard **fields**. If not provided, labels fall back to English)
    - Information text is not translatable
- Time zone seting
  - If we change the personal time zone different from ctz, the records created day will be different
- Single/multi-currency setups
  - single currency is the default
  - multi-currency must be enabled in company information page[every person can show different currency] *inreversibale*
      - Corporate currency is defined
      - Parenthetiical Currency Conversion is enable (in the parethesss)
- Considerations related to Orangization ID
  - 'org ID' is a unique 15 character identifier[product/sandbox]
  - Found in **coompany information page**
- types of license
  - USER Licenses
    - baseline of the feature. Each user must be assigned one license
  - Feature License
    - such as Marketing, knowledge, CRM content
  - Permission License.
- bussiness hour/holidays
  - in case escalation rules and entitlement process
- custom fiscal years and fiscal year configuration
- data and file storage
  - Data storage used by creating records(most is 2KB)
  - file storage used by attachments(e.g. photos)
- Salesforce API[application programming interface]
  - Programatically
    - BUlk data loading(data loader)
