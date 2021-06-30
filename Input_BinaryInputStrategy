#include "Arduino.h"

class InputStrategy {
  protected:
  InputStrategy() {}
};

class Input {
  public:
  Input(InputStrategy* is) {
    inputStrategy = is;
  }
  private:
  InputStrategy *inputStrategy;
};

class BinaryInputStrategy : public InputStrategy {
  public:
  BinaryInputStrategy() {}
};

Input ins = Input(new BinaryInputStrategy());

void setup() { 
  
}
void loop() {
  
}
