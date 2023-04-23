# Задание

## В файл task.py после строки

    faces = face_cascade.detectMultiScale(img_gray)

## необходимо добавить следующий цикл для создания рамки для фиксирования лица: 

    for (x, y, w, h) in faces:
        cv2.rectangle(img, (x, y), (x + w, y + h), (0, 170, 244), 1)
