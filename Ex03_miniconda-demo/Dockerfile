FROM continuumio/miniconda

CMD echo -e "with open('junk.txt', 'w') as f:\n  f.write('#x, y \\\n')\n  for x in range(10):\n    f.write('{}, {} \\\n'.format(x,x**2))" > py_example.py && \
	python py_example.py