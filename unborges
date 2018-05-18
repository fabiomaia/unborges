#! /bin/bash

sed -i '/import genclass.GenericIO;/d' $1
sed -i 's/GenericIO.writeString/System.out.print/g' $1
sed -i 's/GenericIO.writelnString/System.out.println/g' $1
sed -i 's/GenericIO.readlnString *()/System.console().readLine()/g' $1
sed -i 's/GenericIO.readlnInt *()/Integer.parseInt(System.console().readLine())/g' $1
