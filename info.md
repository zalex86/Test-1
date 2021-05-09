# Test-1
my first rep
git add - добавление файла
console
	cd
		смена папки
	mv
		перемещение/переименование
	ls
		список файлов/директорий
		-la
			(наверное все вкл. скрытое)
	cat <file.md>
		показывает содержание md файлов
git
	status
		состояние папки (репозитория)
	config --global core.editor <path>
		назначить редактор
	mv
		перемещение/переименование внутри реп-я с записью в логах
	commit
		фиксировать изменения
		-am
			коммит всего с "сообщением"
		--amend
			открывает редактор для изменения коммита
	add
		<file name>
			добавить файл в репозиторий
		.
			все файлы
	log
		список коммитов
	diff
		не закомиченные изменения (удаления/добавления)
	reset
		<hash>
			возврат к состоянию коммита с хештегом
	stash
		спрятать изменения до коммита
	stash pop
		вернуть спрятанное
	push
		(сервер)
	restore
		<file name>
			вернуть состояние файла к последнему коммиту
			или (checkout -- <path>)
	merge
		stash
			merge
				pull
				pull origin <name>
		(add+commit)
			(checkout)
		merge --abort
		reset --merge
	remote
		remote get-url
		-v
		show origin
	branch
		-m
			(rename)
		-d
			(delete)
		-r 
			(remote rep)
	fetch
		c сервера
			(e.g. origin remote-branch-gh)
	switch
		-c
			(create)(e.g. local-branch)
	help
		branch
		checkout