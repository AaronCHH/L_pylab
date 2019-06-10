# Case1
plt.plot()

# Case2
plt.figure()  |  plt.figure(figsize=(4,3)) 
plt.plot()

ex.
(fig = )plt.figure()
plt.subplot(211)
plt.subplot(212)

# Case3
fig = plt.figure()
ax = fig.add_subplot(111)
ax.plot()

ex1.


# Case4
fig, ax = plt.subplots()
ax.plot()

ex1.
fig, ax = plt.subplots(2)
ax[0].plot(x, np.sin(x))
ax[1].plot(x, np.cos(x))

ex2.
fig, ax = plt.subplots(2, 2)
x = np.linspace(0, 10, 101)
ax[0,0].plot(x, np.sin(x))
ax[1,1].plot(x, np.cos(x))