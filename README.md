# React-Phone-Input-2-Country-Sort


React-Phone-Input-2 (Country Sorted) is a fork of the popular [React Phone Input 2](https://www.npmjs.com/package/react-phone-input-2) library. 

## Notes

**Updated Search Behavior**: 

In the previous version of `react-phone-input-2`, when users typed a letter in the search field (e.g., "M"), the countries containing the letter "M" were displayed first. Now, in this updated version, when a user searches for a letter, such as "M", the countries that **start** with the letter "M" will appear at the top of the search results. 

For example, when searching for "M":

- **Before**: Countries like **"Germany"**, **"Romania"**, etc., would appear first if they contained the letter "M".
- **Now**: Countries like **"Malaysia"**, **"Mexico"**, etc., will appear first as they start with the letter "M".

This change improves the accuracy and efficiency of the search function, making it easier for users to find countries starting with the desired letter.

![animation](https://media.giphy.com/media/xiORAWnqoTJDsH0UOI/giphy.gif)

## Usage
```jsx
import PhoneInput from '@dvij-infotech/react-phone-input-2-country-sort'
import '@dvij-infotech/react-phone-input-2-country-sort/lib/style.css'

<PhoneInput
  country={'us'}
  value={this.state.phone}
  onChange={phone => this.setState({ phone })}
/>

