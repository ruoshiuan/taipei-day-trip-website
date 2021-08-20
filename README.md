# Taipei Day Trip 台北一日遊

## Summary

Taipei Day Trip(台北一日遊) is a simple travel e-commerce website.<br>
With 300+ attraction info from Taipei city open data API, users could click each of the attraction cards to check out the attraction details.<br>
After registering for login, members could book an itinernary and make an order with a credit card payment, or check the order records in the member page.

## Live Demo
### Demo Link

http://52.221.32.164:3000/

### Test account
|    -    |       -       |
| ------- | ------------- |
| Account | test@test.com |
| Password |    tester    |

### Credit Card for test
|      -      |            -              |
| ----------- | ------------------------- |
| Card Number | 4242 - 4242 - 4242 - 4242 |
|  Valid Date |          01 / 23          |
|     CVV     |            123            |


## Built With

| Name                      | Descriptions                                           |
| ------------------------- | ------------------------------------------------------ |
| Intersection Observer API | Realize infinite scrolling page                        |
| Image carousel slider     | Without using library                                  |
| AJAX                      | Call APIs from front-end                               |
| MySQL                     | Store attraction, user data                            |
| Python Flask framework    | Run the server                                         |
| RESTful APIs              | Organize requests for attraction, order, user features |
| AWS EC2                   | Host website                                           |
| TapPay SDK                | Credit card payment                                    |
| Responsive Web Design     | Create web pages that look fine on all devices         |

## Feature

### :small_blue_diamond:Search for attractions

Slide or scroll to the bottom of the index page, the browser will read and display the next 12 attraction cards.<br>
(Also could filter attraction data in the search bar by entering keywords)


<img src="https://user-images.githubusercontent.com/76982122/130183345-a959582c-27b5-45d3-b429-d6fb2967bf2d.png" alt="01" width="650" />

### :small_blue_diamond:Check out the attraction details

Users could click each attraction card in the index page to switch to the attraction detail page.

<img src="https://user-images.githubusercontent.com/76982122/130183352-71d775a6-6e11-4fc8-bc5e-8b9ec8bc5ed7.png" alt="02" width="650" />

### :small_blue_diamond:Place an order

Log in/sign up to become a member after registration, users could book an itinernary and make an order with a credit card payment.

<img src="https://user-images.githubusercontent.com/76982122/130183356-34c590d4-f933-44c4-b9d1-a73b7cefc589.png" alt="03" width="650" />
<img src="https://user-images.githubusercontent.com/76982122/130183359-0f1ab8f6-77ae-4821-9fac-f5dce3df3e1f.png" alt="04" width="650" />
<img src="https://user-images.githubusercontent.com/76982122/130183368-b40b6061-e19f-4d7a-a06d-982117245ec3.png" alt="05" width="650" />

Also, members could check the order records in the member page.

<img src="https://user-images.githubusercontent.com/76982122/130183375-0ed2095a-bd31-4f19-a331-ca78be924735.png" alt="06" width="650" />