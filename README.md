import matplotlib.pyplot as plt
labels = ['Category A', 'Category B', 'Category C', 'Category D']
sizes = [20, 50, 30, 60]
plt.pie(sizes, labels=labels, autopct= '%1.1f%%', startangle=140)
plt.title('My Pie Chart')
plt.show()
