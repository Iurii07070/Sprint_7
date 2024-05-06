<h3 align="center">YANDEX PRACTICUM JAVA AUTOMATION</h3>

## Final Project Sprint 7

## About The Project

The project contains API auto tests for the service [Яндекс.Самокат](https://qa-scooter.praktikum-services.ru/)

## Preparation

Before starting the tasks:

- Create a Maven project.
- Name the project Sprint_7.
- Connect JUnit 4, RestAssured, Allure.
- Test the endpoints

Verify that they work correctly and return the necessary errors.

## courier.CourierClass Creation

Check:

- a courier can be created;
- it's not possible to create two identical couriers;
- to create a courier, you need to pass all required fields to the endpoint;
- the request returns the correct response code;
- a successful request returns ok: true;
- if any of the fields are missing, the request returns an error;
- if you try to create a user with an existing login, an error is returned.

## courier.CourierClass Login

Check:

- a courier can log in;
- to log in, all required fields must be passed;
- the system returns an error if the login or password is incorrect;
- if any field is missing, the request returns an error;
- if you log in with a non-existent user, the request returns an error;
- a successful request returns the id.

## orders.OrderClass Creation

Check that when creating an order:

- you can specify one of the colors — BLACK or GREY;
- you can specify both colors;
- you can omit specifying the color altogether;
- the response body contains track.

To test order creation, use parameterization.

## orders.Orders List

Check that the response body returns a list of orders.

## Allure Report

Generate it and push it to the repository.
