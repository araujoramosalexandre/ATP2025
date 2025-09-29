TPC 1
https://blockly.games/maze?lang=en&level=10&&skin=0#58wtq8
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/4dbb88cf-0d8d-434d-8578-cb8afb9e5d07" />
https://github.com/araujoramosalexandre/ATP2025/blob/main/README.md
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/7220fcea-09b6-4271-83da-7539997cbad2" />
[21.ipynb](https://github.com/user-attachments/files/22585861/21.ipynb)
print("Vamos jogar um jogo. Há 21 fósforos. Cada um pode tirar entre 1 e 4 fósforos de cada vez")
print("Quem tirar o último fósforo perde")
print(21)


a = input("Quem começa? (eu ou tu)")

if a == "eu":
    b = int(input("Quantos fósforos quer remover?"))
    if b==1 or b==2 or b==3 or b==4:
        print("Removeste", b)
        n = 5-b
        print("Eu removo", n)
        print("Restam 16 fósforos")
        c = int(input("Quantos fósforos quer remover?"))
        if c==1 or c==2 or c==3 or c==4:
            print("Removeste", c)
            n = 5-c
            print("Eu removo", n)
            print("Restam 11 fósforos")
            d = int(input("Quantos fósforos quer remover?"))
            if d==1 or d==2 or d==3 or d==4:
                print("Removeste", d)
                n = 5-d
                print("Eu removo", n, "fósforos")
                print("Restam 6 fósforos")
                e = int(input("Quantos fósforos quer remover?"))
                if e==1 or e==2 or e==3 or e==4:
                    print("Removeste", e)
                    n = 5-e
                    print("Eu removo", n)
                    print("Resta 1 fósforo. Perdeste")
                
if a == "tu":
    m=1
    print("Eu removo", m)
    print("Restam 20 fósforos")
    g = int(input("Quantos fósforos quer remover?"))
    if g==1 or g==2 or g==3:
        print("Removeste", g)
        n = 4-g
        print("Eu removo", n)
        print("Restam 16")
        h = int(input("Quantos fósforos quer remover?"))
        if h==1 or h==2 or h==3 or h==4:
            print("Removeste", h)
            n = 5-h
            print("Eu removo", n)
            print("Restam 11 fósforos")
            i = int(input("Quantos fósforos quer remover?"))
            if i==1 or i==2 or i==3 or i==4:
                print("Removeste", i, "fósforos")
                n = 5-i
                print("Eu removo", n)
                print("Restam 6")
                j = int(input("Quantos fósforos quer remover?"))
                if j==1 or j==2 or j==3 or j==4:
                    print("Removeste", j)
                    n = 5-j
                    print("Eu removo", n)
                    print("Resta 1 fósforos. Perdeste")
    if g==4:
        print("Removeste 4")
        print("Restam 16 fósforos")
        print("Eu Removo 1")
        print("Restam 15 fósforos")
        k = int(input("Quantos fósforos quer remover?"))
        if k==1 or k==2 or k==3:
            print("Removeste", k)
            n = 4-k
            print("Eu removo", n)
            print("Restam 11 fósforos")
            i = int(input("Quantos fósforos quer remover?"))
            if i==1 or i==2 or i==3 or i==4:
                print("Removeste", i, "fósforos")
                n = 5-i
                print("Eu removo", n)
                print("Restam 6")
                j = int(input("Quantos fósforos quer remover?"))
                if j==1 or j==2 or j==3 or j==4:
                    print("Removeste", j)
                    n = 5-j
                    print("Eu removo", n)
                    print("Resta 1 fósforo. Perdeste")

        if k==4:
            print("Removeste 4")
            print("Restam 11 fósforos")
            print("Eu Removo 1")
            print("Restam 10 fósforos")
            i = int(input("Quantos fósforos quer remover?"))
            if i==1 or i==2 or i==3:
                print("Removeste", i, "fósforos")
                n = 4-i
                print("Eu removo", n)
                print("Restam 6")
                j = int(input("Quantos fósforos quer remover?"))
                if j==1 or j==2 or j==3 or j==4:
                    print("Removeste", j)
                    n = 5-j
                    print("Eu removo", n)
                    print("Resta 1 fósforo. Perdeste")

            if i==4:
                print("Removeste 4")
                print("Restam 6 fósforos")
                print("Eu Removo 1")
                print("Restam 5 fósforos")
                p = int(input("Quantos fósforos quer remover?"))
                if p==1 or p==2 or p==3:
                    print("Removeste", p)
                    n = 4-p
                    print("Eu removo", n)
                    print("Resta 1 fósforos. Perdeste")
                if p==4:
                    print("Removeste", p)
                    print("Resta 1 fósforo. Ganhaste")
