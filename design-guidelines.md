# Guidelines for Seamless Integration with Developers

## **Responsive Typography**

When designing typography, ensure that text elements are adaptable across all device sizes—mobile, tablet, and web (large screens). Consider the following:

- **Headlines**: For example, when using `Headline1`, ensure it scales appropriately across devices. It should be placed thoughtfully within the layout to maintain visual harmony on different screen sizes.
- **Text Hierarchy**: Establish a clear text hierarchy that remains consistent and readable across devices.

### **Font Sizes**

To maintain consistency in bilingual designs:

- **Uniform Sizing**: Use the same font size for both Arabic and English text. This ensures a consistent look and feel across the application, regardless of the language.

---

## **Design Size System**

Adhere to the established design size system to ensure consistency across all device types—mobile, tablet, and web. This system should guide the sizing of all UI elements to create a cohesive experience, regardless of screen size.

### **Layout and Spacing**

- **Element Distances**: Maintain clear and distinct spacing between elements within a group and between different groups. This helps create a well-organized visual hierarchy and enhances the overall readability and usability of the interface.
- **Consistent Spacing**: Use consistent spacing values as defined in the design system for different device sizes, ensuring that layouts look balanced and harmonious across all platforms.
- **Grid System**: Employ a grid system to align elements and ensure consistency in layout and spacing.

### Uniform Padding and Border Radius

- **Consistent Values**: Strive to use uniform padding and border radius values across different components and layouts. This ensures a cohesive and polished appearance throughout the application.
- **Adaptive Padding**: Define padding values that adapt based on the device size:
    - **Desktop**: `primaryPadding` = 10px
    - **Tablet**: `primaryPadding` = 8px
    - **Mobile**: `primaryPadding` = 6px
- **Design System Control**: Manage these padding and border radius values within the design system, ensuring that changes are made globally rather than in individual code elements. This approach promotes consistency and simplifies maintenance.
- **Padding and Margin**: Apply consistent padding and margin values throughout the design (It is preferable to follow the standards always used, for example, in mobile from 18-22).

---

## Color and Contrast Guidelines

### **Uniform Color Tones**

- **Consistency**: Maintain uniform color tones throughout the design to create a cohesive visual experience. Avoid unnecessary variations in color to ensure a clean and professional look.
- **Standard Naming Conventions**: Use clear and semantic naming for colors to enhance collaboration and maintain consistency. Examples include:
    - **Semantic Names**: `greyDarker`, `greyDark`, `grey`, `greyLight`, `greyLighter`
    - **Functional Names**: `primary`, `onPrimary`, `background`, `onBackground`

### **Gradients and Layers**

- **Avoid Misalignment**: When working with gradients, ensure they are properly aligned within the frame. Misaligned gradients can disrupt the visual flow of the design.
- **Limited Use of Gradients**: Avoid using multiple colors or gradients within the same frame. Instead, apply each style using separate layers to maintain clarity and flexibility in design adjustments.

### **Opacity and Tones**

- **Avoid Opacity Within Frames**: Refrain from using opacity adjustments directly within frames. Instead, use predefined color variables or tone variations to achieve the desired effect without compromising design integrity.

---

## Icons and Images Guidelines

- **Uniform Sizing**: Ensure that icon sizes are consistent across similar elements, such as within cards or lists. This helps maintain visual harmony and balance in the design.
- **Scalability with SVGs**: Use SVGs for icons whenever possible. SVGs offer scalability and clarity at any size, ensuring that icons look crisp and sharp across all devices and screen resolutions.

---

## Buttons and Interactions Guidelines

### **Unified Buttons Across Devices**

- **Consistency Across Platforms**: Design buttons to be consistent across mobile, tablet, and web. Ensure that the appearance and behavior of buttons are unified, adapting appropriately to different screen sizes without losing their core style and functionality.

### **Button Styles**

- **Standardized Styles**: Use consistent button styles throughout the application, such as `primary` and `secondary` buttons. This consistency helps users quickly recognize and understand the purpose of each button.

### **Hover and Active States**

- **Clear Feedback**: Design distinct hover and active states for all interactive elements. These states should provide clear visual feedback to users, enhancing the overall interactivity and usability of the application.

---

## Forms and Inputs Guidelines

- **Focus State**: Define a clear and consistent style for input fields when they are focused. This should include visual cues like border color, shadow, or background change to indicate that the field is active and ready for user input.
- **Validation Error State**: Ensure that input fields display a distinct and easily recognizable style when there is a validation error. This might include changing the border color to red, displaying an error icon, or showing an error message below the field. The error state should be immediately apparent to users, helping them quickly identify and correct mistakes.

---

## Animations and Transitions

- **Subtle Animations**: Use subtle animations to enhance user experience without distracting users.
- **Performance**: Ensure animations do not negatively impact performance.
- **Consistency**: Maintain consistency in animation styles and durations across the application.

---

## Component Change Guidelines

- **Identify All States**: When making changes to a component, ensure that all possible states and variations of the component are considered. This includes different sizes, hover and active states, focused states, error states, and any other conditional styles or behaviors.
- **Consistency Across Devices**: Review how the component behaves and appears across different devices (mobile, tablet, web). Ensure that changes are consistently applied across all platforms.
- **Design System Updates**: Update the design system with any changes to components, ensuring that the modifications are propagated throughout the entire system. This prevents inconsistencies and ensures that everyone is using the latest version of the component.
- **Notification of Changes**: If any changes are made to a component or its states, promptly notify the responsible person. This ensures that everyone is aware of the updates and can take appropriate action if needed.

---

## General Guidelines

### **Use Semantic Icon and Image Names**

- **Consistent Naming**: Always use semantic names for icons and images. This practice enhances clarity and makes it easier for team members to identify and work with these assets consistently.

### **Responsive Design Over Adaptive Design Inside Cards or Groups**

- **Responsive First**: Prioritize responsive design within cards or groups of elements. Focus on creating designs that adapt fluidly across different screen sizes, rather than relying on adaptive techniques that involve separate designs for each device. This approach ensures a more consistent and seamless user experience across all platforms.

### **Utilizing Material 3 Components**

- **Material 3 as a Foundation**: Use Material 3 components within Flutter as the base for your designs. Whenever possible, customize these components to fit project needs, ensuring that your designs are aligned with Flutter’s best practices and maintain consistency across the application.
