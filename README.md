# CommandHandler
Command Handle Protocol (Command Handler) Universal way to execute tasks

Так вот для этого я придумал Command Handle Protocol
Идея очень простая. 
С позиции протокола сообщения делятся на две части: [команда][данные...]

Таким образом вне зависимости от того по какому каналу пришли данные на включение компьютера их можно удобно выполнить данными обработчиком
