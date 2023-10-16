
# bitgrow_backend

bitgrow_backend is a Django backend application designed for managing and creating orders/kols/projects/tasks api for BitGrow application. 

## Features

- list orders
- list tasks
- list kols
- list projects
- create order
- create task
- create kol
- create project
- update order status
- update task info
- update project info
- update kol info
- filter kol by 'portrait', 'language', 'area', 'address', 'fans_gt'
- filter order by 'order_id', 'task_id', 'kol', 'kol_name', 'kol_address', 'status'
- filter task by 'project'
- sign message by 

## Tech Stack

- Django [4.2.6]
- Python [3.11.2]
- django-filter [23.3]
- django-import-export [3.3.1]
- djangorestframework [3.14.0]
- gunicorn [21.2.0]
- nginx [njs-0.8.1]
- celery [5.3.4]

## Installation

Make sure you have Python and pip installed. Then, follow these steps to set up the project:

1. Clone this repository:

   ```
   git clone https://github.com/Bitgrow-xyz/bitgrow_backend.git
   ```

2. Navigate to the project directory:

   ```
   cd your-project
   ```

3. Create and activate a virtual environment (optional but recommended):

   ```
   python -m venv venv
   source venv/bin/activate
   ```

4. Install project dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Run database migrations:

   ```
   python manage.py migrate
   ```

2. Start the development server:

   ```
   python manage.py runserver
   ```

3. Open a web browser and go to [http://localhost:8000](http://localhost:8000) to view the project.

## Contributing

If you'd like to contribute to this project, feel free to suggest improvements or submit a pull request. Here are some possible ways to contribute:

- **Bug Fixes:** Identify and fix bugs or issues reported by users or discovered during your own testing.

- **Feature Development:** Contribute to the development of new features or functionalities for this project. This could involve coding new functionalities, writing tests, and updating documentation.

- **Documentation:** Improve project documentation, including README files, code comments, and user guides. Clear and well-documented code is essential for a successful open-source project.

- **Code Reviews:** Participate in code reviews by reviewing and providing feedback on pull requests submitted by other contributors. Code reviews help maintain code quality and consistency.

- **Testing:** Write and execute test cases to ensure the project's functionality remains stable. You can contribute by creating new tests or enhancing existing ones.

- **Performance Optimization:** Identify and implement improvements to optimize the project's performance. This could involve profiling code, finding bottlenecks, and suggesting optimizations.

- **Translations:** If the project is internationalized, you can help by providing translations for different languages.

- **User Support:** Assist users by answering questions, providing support in issue discussions, or helping troubleshoot problems they encounter while using the project.

- **Security Audits:** Conduct security audits to identify and address potential security vulnerabilities in the project.

- **Refactoring:** Help improve the project's codebase by refactoring code to make it more maintainable, readable, and efficient.

## License

This project is licensed under the MIT License.

## Contact

If you have any questions or need further assistance, please contact UnknownMusketeer(live in metaverse).

