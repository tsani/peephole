# assumes sablecc script is on your PATH

# to compile the code
joosc: clean
	@$(PEEPDIR)/joosc $(JOOSCOPTS) *.java

java: clean
	@javac *.java

check:	
	@./check.py

clean:	
	@rm -rf *.class *.j
