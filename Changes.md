
--
## Changes Made to the Website

### Frontend
- **Carousel Simplification:** Replaced multiple carousels with a single carousel that changes automatically.
- **Task Display:** Simplified the task structure by removing the nested "box inside a box" format.
- **Dynamic Routes:** Implemented dynamic routing for tasks, resulting in less JavaScript code being sent to the client. This enhances the website's speed.
- **Image Optimization:**Can Utilize `.webp` image format for faster loading times compared to `.png`.
- **User Interface:** Focused on a simple and user-friendly UI inspired by the "Groww" platform, which is known for its straightforward interface, contributing to its status as the number one brokerage site in India, surpassing Zerodha.

### Backend
- **REST APIs and Status Codes:** Followed REST principles and included appropriate status codes for API responses.
- **CRUD Operations:** Implemented the ability to create and delete tasks. Additionally, included the code for updating tasks.
- **Admin Authentication:** Ensured that only authenticated admins can modify or add tasks. If the admin is not authenticated, the system redirects them to the homepage.

