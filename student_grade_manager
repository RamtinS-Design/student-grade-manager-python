students = []
grades = []

num_students = int(input('How many students? '))
for item in range(num_students):
    print(f'\nStudent {item+1}:')

    name = input('Enter Student Name: ').strip()

    while True:
        grade = float(input('Enter Student Grade: '))
        if 0 <= grade <= 100:
            break
        print('Please enter a grade between 0 and 100.')

    students.append(name)
    grades.append(grade)

average = sum(grades) / len(grades)

highest_grade = max(grades)
top_index = grades.index(highest_grade)
top_student = students[top_index]

print('\n--- Results ---')
print('Class Average:', average)
print('Class Highest Grade:', highest_grade)
print('Class Top Student:', top_student)

print('\nStudent Grades:')
for item in range(len(students)):
    print(students[item], ':', grades[item])



