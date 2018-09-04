Roman Numerals Generator 

Converts from integers to Roman numerals. Input value range of 1-3999. Exceptions are thrown for numbers out of this range.
Main has a method to test value input and outputs.

Classes: 
CreateRomanNumeral - generate(int)
Main - IntRomanPair(int),CreateRomanNumeral()
RomanNumeralGenerator - generate(int)
RomanNumerals - TreeMap(key, value)
RomanGeneratorTests - See break down of tests

Running the tests:
Main has testable input-output values. There is additionally a test class with JUNIT tests. These will run and provide 
to assert equals or assert null for a set of pre-selectd outcomes. 

Break down of tests: 
public void setUp()- Tests the romanGenerator before
public void testMinimum()-Tests the minimum value of 1
public void testMaximum() - Tests maximum vaue of 3999
public void testValidMin() - Test minimum value is 1 or greater 
public void testValidMax() - Tests maximum value is less than or equal to 3999
public void testZero() - Tests that 0 imput would result in null
public void testValue43() - Tests that value 43 is correctly converted to Roman Numeral


Deployment -
Run Main class

Built With -
Java+Eclipse 


Authors
Courtnee Mendes-Persson

