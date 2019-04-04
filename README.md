# Homework-6-OOD
OOD - Dr. Shomper class Spring 2019
// Test
#pragma once

// Wire Class cpp file for Term-Project
// Author: Aaron Johnston
// 4-3-19
using namespace std;
#include <string>
#include <vector>
#include "wire.h"

void Wire::getDataWire() {
	 
}

Wire::Wire() {
	isInput = true; // Just had to pick one.. default assuming it is an input
	name = "A";
	wireNum = 1;
}

Wire::Wire(bool wIsInput, string wName, int wWireNum) {
	isInput = wIsInput;
	name = wName;
	wireNum = wWireNum;
}

int Wire::getWireNum(){
	return wireNum;
}

void Wire::setWireNum(int wNum) {
	wireNum = wNum;
}

string Wire::getName() {
	return name;
}

void Wire::setName(string wName) {
	name = wName;
}
