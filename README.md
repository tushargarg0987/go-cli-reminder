# Go Reminder CLI

A simple command-line reminder tool written in Golang that allows you to set reminders with a specific time and accompanying text.

## Usage

```bash
go-cli-reminder <hh:mm> <text>
```

- **time**: The time at which you want to be reminded in the format HH:MM.
- **text**: The text message or reminder you want to associate with the specified time.

## Example

```bash
go-cli-reminder 14:30 Meeting with Team
```

This will set a reminder for 2:30 PM with the message "Meeting with Team."

## Installation

1. Make sure you have Go installed on your machine.

2. Clone the repository:

```bash
git clone https://github.com/tushargarg0987/go-cli-reminder.git
```

3. Navigate to the project directory:

```bash
cd go-cli-reminder
```

4. Build the executable:

```bash
go build
```

5. Run the program:

```bash
./go-cli-reminder [time] [text]
```

## Contributing

If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request. Your contributions are always welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.