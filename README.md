# function-w-parameters

Functions with parameters are functions that have an argument passed through it. The arguments need to be declared a datatype when passed in the function.
For example,
void Function(int x){
  int result = x / 2;
  print(result);
}

public int Function(int x, int y){
  int result = y + x / 2;
  return result;
}

int Function(int x){
  int result = x - 6;
  print(result);
}

void Function(int pizza){
  int result = pizza + 3;
  print(result);
}

void Function(int pizza, int pepperoni){
  int result = pepperoni - pizza + 3;
  print(result);
}

void Function(int y){
  int result = y;
  print(result);
}

public float myFunction(float r, float s, float t){
  float result = (r / s/ t) - 5;
  return result;
}

int myFunction(int goat){
  int result = goat / 2 - 6;
  return result;
}

int myFunction(int x, int y, int z){
  int result = x / 3 - y + z / 3;
  return result;
}
