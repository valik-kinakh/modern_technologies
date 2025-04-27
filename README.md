# 🧪 Panorama Studio Hall Booking - Manual Test Cases

This document contains 130 manual test cases designed to validate the functionality, performance, usability, and security of the Panorama Studio Hall Booking system, specifically at the hall selection stage.

---

## ✅ Test Cases

---

### 1. Functional Test Cases (1–50)

1. Verify that all available halls are listed.
2. Verify that hall details (name, capacity, features) are displayed correctly.
3. Verify that selecting a hall highlights it appropriately.
4. Verify that only one hall can be selected at a time.
5. Verify that the "Next" button becomes enabled after selecting a hall.
6. Verify that clicking "Next" without selecting a hall prompts an error.
7. Verify that hall images are displayed correctly.
8. Verify that hall availability status is accurate.
9. Verify that unavailable halls are either hidden or marked as unavailable.
10. Verify that hall selection persists when navigating back and forth.
11. Verify that the date picker allows selection of valid dates.
12. Verify that past dates cannot be selected.
13. Verify that time slots are displayed based on the selected date.
14. Verify that selecting a time slot updates the booking summary.
15. Verify that overlapping time slots cannot be selected.
16. Verify that the system prevents double bookings for the same time slot.
17. Verify that time slots are displayed in the correct format.
18. Verify that the duration of the booking is calculated correctly.
19. Verify that changing the date resets the selected time slot.
20. Verify that the system handles daylight saving time changes appropriately.
21. Verify that user can input their name.
22. Verify that user can input their contact number.
23. Verify that user can input their email address.
24. Verify that mandatory fields are marked appropriately.
25. Verify that the system validates the email format.
26. Verify that the system validates the contact number format.
27. Verify that the system prevents submission with empty mandatory fields.
28. Verify that special characters are handled correctly in input fields.
29. Verify that the system trims leading and trailing spaces in inputs.
30. Verify that the user can add additional notes or requests.
31. Verify that the payment page displays the correct booking summary.
32. Verify that available payment methods are displayed.
33. Verify that selecting a payment method updates the payment form accordingly.
34. Verify that the system validates credit card numbers.
35. Verify that the system validates CVV codes.
36. Verify that the system validates expiration dates.
37. Verify that the payment amount matches the booking summary.
38. Verify that the system handles payment failures gracefully.
39. Verify that a confirmation message is displayed upon successful payment.
40. Verify that a confirmation email is sent after successful payment.
41. Verify that the booking confirmation page displays all relevant details.
42. Verify that the user can download or print the booking confirmation.
43. Verify that the booking reference number is unique.
44. Verify that the user can view their booking history.
45. Verify that the user can cancel their booking within allowed timeframes.
46. Verify that the system updates availability after a booking is made.
47. Verify that the system prevents duplicate bookings for the same time slot.
48. Verify that the system handles simultaneous bookings appropriately.
49. Verify that the booking details are stored securely.
50. Verify that the user receives notifications for any changes to their booking.

---

### 2. UI/UX Test Cases (51–60)
51. Verify that the website is responsive across devices (desktop, tablet, mobile).
52. Verify that fonts and colors are consistent throughout the booking process.
53. Verify that buttons and links are clearly labeled and functional.
54. Verify that error messages are displayed in a user-friendly manner.
55. Verify that loading indicators are displayed during data fetches.
56. Verify that the navigation menu is accessible and functional.
57. Verify that images are optimized for fast loading.
58. Verify that the layout remains consistent across different browsers.
59. Verify that the booking steps are clearly indicated.
60. Verify that the language selection option is available and functional.

---

### 3. Security Test Cases (61–70)

61. Verify that user data is transmitted over HTTPS.
62. Verify that input fields are protected against SQL injection.
63. Verify that the system implements CSRF protection.
64. Verify that user sessions expire after a period of inactivity.
65. Verify that password fields are masked.
66. Verify that the system enforces strong password policies.
67. Verify that users cannot access other users' booking details.
68. Verify that the system logs out users after password changes.
69. Verify that the system limits login attempts to prevent brute-force attacks.
70. Verify that session cookies are marked as HttpOnly and Secure.

---

### 4. Localization Test Cases (71–75)

71. Verify that the interface supports multiple languages (e.g., Ukrainian, English).
72. Verify that date and time formats change appropriately with locale selection.
73. Verify that translations are accurate and professional across the UI.
74. Verify that currency changes according to selected country (if applicable).
75. Verify that the language preference is saved between sessions.

---

### 5. Performance & Load Test Cases (76–80)

76. Verify that the page loads within acceptable time under normal conditions.
77. Verify that the hall selection page can handle high traffic without breaking.
78. Verify that selecting a hall and proceeding through the steps is fast and seamless.
79. Verify system behavior when 100+ concurrent users attempt to book the same hall.
80. Verify that large images do not impact performance.

---

### 6. Mobile Device Compatibility (81–85)

81. Verify that the hall selection layout adjusts correctly on smaller screens.
82. Verify that form elements are tappable and accessible on mobile devices.
83. Verify that the date/time picker works correctly on mobile browsers.
84. Verify that the payment page is responsive on tablets.
85. Verify that touch gestures like scrolling and zooming are smooth.

---

### 7. Compatibility Testing (86–90)

86. Verify that the site works correctly on Chrome.
87. Verify that the site works correctly on Firefox.
88. Verify that the site works correctly on Safari.
89. Verify that the site works correctly on Edge.
90. Verify functionality on older browser versions (e.g., IE11 if supported).

---

### 8. Edge Cases (91–100)

91. Verify behavior when user tries to go back using the browser back button.
92. Verify behavior when the booking page is refreshed in the middle of the process.
93. Verify behavior when cookies are disabled in the browser.
94. Verify that extremely long names or emails do not break the layout.
95. Verify handling of booking starting at 23:00 (crossing to next day).
96. Verify user input with only spaces is not accepted.
97. Verify inputs with emojis or uncommon Unicode characters.
98. Verify behavior if payment provider service is unavailable.
99. Verify maximum allowed length for all text input fields.
100. Verify user is warned before leaving the booking process mid-way.

---

### 9. Integration Test Cases (101–105)

101. Verify that booking data is correctly sent to backend services.
102. Verify integration with email service for confirmation mail.
103. Verify integration with calendar system if available.
104. Verify that booked times are synced across all connected systems.
105. Verify webhook triggers for booking lifecycle events (if supported).

---
### 10. Additional Scenarios (106–130)

106. Verify network loss during booking is handled gracefully.
107. Verify booking after midnight is accepted and shown on the correct date.
108. Verify that a booking can span over multiple hours without errors.
109. Verify changing selected hall resets date and time selections.
110. Verify changing selected hall preserves user data in booking form.
111. Verify repeated selection of the same hall doesn’t break UI.
112. Verify input fields accept Ukrainian characters.
113. Verify input fields accept Latin characters.
114. Verify special characters do not crash the form.
115. Verify negative testing on every required field.
116. Verify payment attempt with an expired card is rejected.
117. Verify entering invalid CVV throws proper validation error.
118. Verify switching tabs mid-booking doesn’t reset booking data.
119. Verify canceling at payment redirects user back to booking step.
120. Verify logout during booking clears current session.
121. Verify booking confirmation is accessible through user’s account.
122. Verify email includes correct hall name and time.
123. Verify input validation for long phone numbers.
124. Verify placeholder text is visible in all input fields.
125. Verify accessibility (keyboard navigation and screen reader labels).
126. Verify browser autofill suggestions in form fields.
127. Verify correct title and favicon for the page.
128. Verify booking in the far future (e.g., +1 year) is supported.
129. Verify booking during blocked dates (e.g., holidays) is disabled.
130. Verify session timeout behavior after inactivity.

---
