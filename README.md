def Python Killer(n):
	try:
		for x in range(10000):
		     print 5
		raise KeyboardInterrupt
	except KeyboardInterrupt:
		print 'Goodbye World!'
		quit()
