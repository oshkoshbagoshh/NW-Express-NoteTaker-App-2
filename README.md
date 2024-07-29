# Note Taker Application

## Description

The Note Taker application is a simple yet powerful tool that allows users to write, save, and delete notes. This application uses an Express.js back end and saves and retrieves note data from a JSON file.

## Features

- View existing notes
- Create and save new notes
- Delete existing notes
- Responsive design for use on various devices

---

## API Routes

- GET `/api/notes` - Reads the `db.json` file and returns all saved notes as JSON.
- POST `/api/notes` - Receives a new note to save on the request body, adds it to the `db.json` file, and then returns the new note to the client.
- DELETE `/api/notes/:id` - Receives a query parameter containing the id of a note to delete, removes the note with the given `id` property, and then rewrites the notes to the `db.json` file.

## Contributing

Contributions to improve the Note Taker application are welcome. Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

## Contact

AJ Javadi - amirjavadi25@gmail.com

Project Link: [https://github.com/your-username/note-taker](https://github.com/your-username/note-taker)
