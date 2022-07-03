#!/usr/bin/python
# -*- coding: utf-8 -*-
class SoftwareEngineer:

    def __init__(self):
        self.name = "Abraar"
        self.role = "SWE Student"
        self.tools = ["C/C++", "Python", "Java"]
        self.learning = ["Julia"]

    def say_hi(self):
        print("Thanks for dropping by, hope you find"
                    "some of my work interesting.")

me = SoftwareEngineer()
me.say_hi()
