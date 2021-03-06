cmake_minimum_required(VERSION 3.17)
project(DesignPatterns)

set(CMAKE_CXX_STANDARD 14)

add_executable(Observer BehavioralPatterns/Observer/observer.cpp)

add_executable(Abstract_Factory CreationalPatterns/AbstractFactory/abstractFactory.cpp)
add_executable(Builder CreationalPatterns/Builder/builder.cpp)
add_executable(Factory_Method CreationalPatterns/FactoryMethod/factoryMethod.cpp)
add_executable(Object_Pool CreationalPatterns/ObjectPool/objectPool.cpp)
add_executable(Prototype CreationalPatterns/Prototype/prototype.cpp)
add_executable(Singleton CreationalPatterns/Singleton/singleton.cpp)

add_executable(Adapter StructuralPatterns/Adapter/adapter.cpp)
add_executable(Bridge StructuralPatterns/Bridge/bridge.cpp)
add_executable(Composite StructuralPatterns/Composite/composite.cpp)
add_executable(Decorator StructuralPatterns/Decorator/decorator.cpp)
add_executable(Facade StructuralPatterns/Facade/facade.cpp)
add_executable(Flyweight StructuralPatterns/Flyweight/flyweight.cpp)
add_executable(Proxy StructuralPatterns/Proxy/proxy.cpp)
