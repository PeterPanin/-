# -
润平年判断器
year = int(input('请输入一个年份：'))
if year % 4 == 0 and year % 100 != 0 or year % 400 == year:
    print(f'{year}年是闰年')
else:
    print(f'{year}年是平年')
