from PIL import Image
import os

directory = 'X:\\spreadshirtshirts\\new2\\new'
c = 1

os.chdir(r'X:\\spreadshirtshirts\\new2\\new')

for filename in os.listdir(directory):
    if filename.endswith(".jpg"):
        im = Image.open(filename)
        name = 'img' + str(c) + '.png'
        rgb_im = im.convert('RGB')
        rgb_im.save(name)
        c += 1
        print(os.path.join(directory, filename))
        continue
    else:
        continue
