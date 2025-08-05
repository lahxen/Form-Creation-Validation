# Form Creation and Validation

A responsive user registration form with advanced client-side validation using HTML5, CSS3, and vanilla JavaScript.

## Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Real-time Validation**: Immediate feedback as users type
- **Advanced Password Requirements**: Enforces strong password policies
- **User-friendly Interface**: Clean, modern design with smooth animations
- **Accessibility**: Proper form labels and ARIA attributes
- **Cross-browser Compatibility**: Works on all modern browsers

## Form Fields

1. **Full Name**: Validates for alphabetic characters and spaces (2-50 characters)
2. **Email Address**: Validates proper email format
3. **Phone Number**: Validates international phone number formats
4. **Password**: Requires at least 8 characters with:
   - At least one uppercase letter
   - At least one lowercase letter
   - At least one number
   - At least one special character (@$!%*?&)
5. **Confirm Password**: Must match the password field

## Validation Features

- **Real-time validation** on blur and input events
- **Visual feedback** with color-coded borders (green for valid, red for invalid)
- **Detailed error messages** for each validation rule
- **Form submission prevention** until all fields are valid
- **Success feedback** after successful submission

## Files Structure

```
├── index.html      # Main HTML structure
├── style.css       # CSS styling and responsive design
├── script.js       # JavaScript validation logic
└── README.md       # Project documentation
```

## How to Run

1. Clone this repository
2. Open `index.html` in any modern web browser
3. Fill out the form and test the validation features

## Technologies Used

- **HTML5**: Semantic markup and form structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Form validation and DOM manipulation
- **Responsive Design**: Mobile-first approach

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

This project is open source and available under the [MIT License](LICENSE).
