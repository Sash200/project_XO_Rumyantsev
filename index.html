
def show_field(f):
    num ='  0 1 2'
    print(num)
    for row,i in zip(f,num.split()):
        print (f"{i} {' '.join(str(j) for j in row)}")

def users_input(f,user):
    while True:
        place=input(f"Ходит {user}, введите две координаты через пробел (горизонталь вертикаль):").split()
        if len(place)!=2:
            print('Не верный ввод данных, введите координаты (числа)')
            continue
        if not(place[0].isdigit() and place[1].isdigit()):
            print('Не верный ввод данных, введите числа координат от 0 до 2 включительн')
            continue
        x, y = map(int, place)
        if not(x>=0 and x<3 and y>=0 and  y<3):
            print('Не верный ввод данных, превышен интервал одной из координат. Введите числа от 0 до 2 включительно')
            continue
        if f[x][y]!='-':
            print('Клетка занята')
            continue
        break
    return x,y


def win_position(f,user):
    f_list=[]
    for l in f:
        f_list+=l
    positions=[[0,1,2],[3,4,5],[6,7,8],[0,3,6],[1,4,7],[2,5,8],[0,4,8],[2,4,6]]
    indices = set([i for i, x in enumerate(f_list) if x == user])

    for p in positions:
        if len(indices.intersection(set(p)))==3:
            return True
    return False

def start(field):

    count=0
    while True:
        show_field(field)
        if count%2==0:
            user='x'
        else:
            user = 'o'
        if count<9:
            x, y = users_input(field,user)
            field[x][y] = user

        elif count==9:
            print ('Ничья')
            break
        if win_position(field,user):
            print(f"Выйграл {user}")
            break
        count+=1

field = [['-'] * 3 for _ in range(3)]

start(field)
