## interactive_story_1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - action_chk_location
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget_min": "300", "budget_max": "700"}
    - slot{"budget_max": "700"}
    - slot{"budget_min": "300"}
    - action_search_restaurants
    - utter_email_conf
* restaurant_search{"email_id": "chebroluharika@gmail.com"}
    - slot{"email_id": "chebroluharika@gmail.com"}
    - action_send_email
    - utter_email_sent

## interactive_story_2
* greet
    - utter_greet
* restaurant_search{"location": "Rishikesh"}
    - slot{"location": "Rishikesh"}
    - action_chk_location
    - slot{"location": null}
* restaurant_search{"location": "Prayagraj"}
    - slot{"location": "Prayagraj"}
    - action_chk_location
    - slot{"location": "Prayagraj"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget_min": "700"}
    - slot{"budget_min": "700"}
    - action_search_restaurants
    - utter_email_conf
* restaurant_search{"email_id": "chebroluharika@gmail.com"}
    - slot{"email_id": "chebroluharika@gmail.com"}
    - action_send_email
    - utter_email_sent

## interactive_story_3
* greet
    - utter_greet
* restaurant_search{"location": "kolkota"}
    - slot{"location": "kolkota"}
    - action_chk_location
    - slot{"location": null}
* restaurant_search{"location": "Kolkata"}
    - slot{"location": "Kolkata"}
    - action_chk_location
    - slot{"location": "Kolkata"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget_max": "300"}
    - slot{"budget_max": "300"}
    - action_search_restaurants
    - utter_email_conf
* affirm
* restaurant_search{"email_id": "chebroluharika@gmail.com"}
    - slot{"email_id": "chebroluharika@gmail.com"}
    - action_send_email
    - utter_email_sent

## interactive_story_4_final
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mubaim"}
    - slot{"location": "mubaim"}
    - action_chk_location
    - slot{"location": null}
* restaurant_search{"location": "Mumbai"}
    - slot{"location": "Mumbai"}
    - action_chk_location
    - slot{"location": "Mumbai"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget_min": "0", "budget_max": "300"}
    - slot{"budget_max": "300"}
    - slot{"budget_min": "0"}
    - action_search_restaurants
    - utter_email_conf
* affirm
    - utter_ask_email_id
* restaurant_search{"email_id": "chebroluharika@gmail.com"}
    - slot{"email_id": "chebroluharika@gmail.com"}
    - action_send_email
    - utter_email_sent

## interactive_story_5
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "chandigarh"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "chandigarh"}
    - action_chk_location
    - slot{"location": "chandigarh"}
    - utter_ask_budget
* restaurant_search{"budget_max": "300"}
    - slot{"budget_max": "300"}
    - action_search_restaurants
    - utter_email_conf
* deny
    - utter_goodbye

## interactive_story_6
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "bangalore"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "bangalore"}
    - action_chk_location
    - slot{"location": "bangalore"}
    - utter_ask_budget
* restaurant_search{"budget_min": "300", "budget_max": "700"}
    - slot{"budget_max": "700"}
    - slot{"budget_min": "300"}
    - action_search_restaurants
    - utter_email_conf
* affirm
    - utter_ask_email_id
* restaurant_search{"email_id": "chebroluharika@gmail.com"}
    - slot{"email_id": "chebroluharika@gmail.com"}
    - action_send_email
    - utter_email_sent

## interactive_story_7
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "chandigarh"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "chandigarh"}
    - action_chk_location
    - slot{"location": "chandigarh"}
    - utter_ask_budget
* restaurant_search{"budget_max": "300"}
    - slot{"budget_max": "300"}
    - action_search_restaurants
    - utter_email_conf
* affirm
    - utter_ask_email_id
* restaurant_search{"email_id": "chebroluharika@gmail.com"}
    - slot{"email_id": "chebroluharika@gmail.com"}
    - action_send_email
    - utter_email_sent

## interactive_story_8
* greet
    - utter_greet
* restaurant_search{"cuisine": "Italian", "location": "ghazipur"}
    - slot{"cuisine": "Italian"}
    - slot{"location": "ghazipur"}
    - action_chk_location
    - slot{"location": null}
* restaurant_search{"location": "Hyderabad"}
    - slot{"location": "Hyderabad"}
    - action_chk_location
    - slot{"location": "Hyderabad"}
    - utter_ask_budget
* restaurant_search{"budget_min": "300", "budget_max": "700"}
    - slot{"budget_max": "700"}
    - slot{"budget_min": "300"}
    - action_search_restaurants
    - utter_email_conf
* affirm
    - utter_ask_email_id
* restaurant_search{"email_id": "chebroluharika@gmail.com"}
    - slot{"email_id": "chebroluharika@gmail.com"}
    - action_send_email
    - utter_email_sent

## interactive_story_9
* greet
    - utter_greet
* restaurant_search{"location": "aligarh"}
    - slot{"location": "aligarh"}
    - action_chk_location
    - slot{"location": "aligarh"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - utter_ask_budget
* restaurant_search{"budget_min": "200", "budget_max": "500"}
    - slot{"budget_max": "500"}
    - slot{"budget_min": "200"}
    - action_search_restaurants
    - utter_email_conf
* affirm
    - utter_ask_email_id
* send_mail{"email_id": "goyal1992.vibhor@gmail.com"}
    - slot{"email_id": "goyal1992.vibhor@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_10
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Aligarh"}
    - slot{"location": "Aligarh"}
    - action_chk_location
    - slot{"location": "Aligarh"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget_min": "300", "budget_max": "700"}
    - slot{"budget_max": "700"}
    - slot{"budget_min": "300"}
    - action_search_restaurants
    - utter_email_conf
* affirm
    - utter_ask_email_id
* send_mail{"email_id": "goyal1992.vibhor@gmail.com"}
    - slot{"email_id": "goyal1992.vibhor@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_11
* greet
    - utter_greet
* restaurant_search{"location": "Rishikesh"}
    - slot{"location": "Rishikesh"}
    - action_chk_location
    - slot{"location": null}
* restaurant_search{"location": "Prayagraj"}
    - slot{"location": "Prayagraj"}
    - action_chk_location
    - slot{"location": "Prayagraj"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget_min": "700"}
    - slot{"budget_min": "700"}
    - action_search_restaurants
    - utter_email_conf
* deny
    - utter_goodbye
    - action_restart

## interactive_story_12
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "chandigarh"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "chandigarh"}
    - action_chk_location
    - slot{"location": "chandigarh"}
    - utter_ask_budget
* restaurant_search{"budget_min": "0", "budget_max": "300"}
    - slot{"budget_max": "300"}
    - slot{"budget_min": "0"}
    - action_search_restaurants
    - utter_email_conf
* deny
    - utter_goodbye
    - action_restart

## interactive_story_13
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_chk_location
    - slot{"location": "Bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget_min": "300", "budget_max": "700"}
    - slot{"budget_max": "700"}
    - slot{"budget_min": "300"}
    - action_search_restaurants
    - utter_email_conf
* send_mail{"email_id": "goyal1992.vibhor@gmail.com"}
    - slot{"email_id": "goyal1992.vibhor@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_14
* greet
    - utter_greet
* restaurant_search{"location": "Rishikesh"}
    - slot{"location": "Rishikesh"}
    - action_chk_location
    - slot{"location": null}
* restaurant_search{"location": "Prayagraj"}
    - slot{"location": "Prayagraj"}
    - action_chk_location
    - slot{"location": "Prayagraj"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_budget
* restaurant_search{"budget_min": "700"}
    - slot{"budget_min": "700"}
    - action_search_restaurants
    - utter_email_conf
* send_mail{"email_id": "goyal1992.vibhor@gmail.com"}
    - slot{"email_id": "goyal1992.vibhor@gmail.com"}
    - action_send_email
    - utter_email_sent
    - action_restart

## interactive_story_15
* greet
    - utter_greet
* restaurant_search{"location": "Kolkata"}
    - slot{"location": "Kolkata"}
    - action_chk_location
    - slot{"location": "Kolkata"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "American"}
    - slot{"cuisine": "American"}
    - utter_ask_budget
* restaurant_search{"budget_max": "300"}
    - slot{"budget_max": "300"}
    - action_search_restaurants
* affirm
* restaurant_search{"cuisine": "North Indian"}
    - slot{"cuisine": "North Indian"}
    - action_search_restaurants
* deny
    - utter_goodbye
    - action_restart

## interactive_story_16
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_chk_location
    - slot{"location": "Bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "Mexican"}
    - slot{"cuisine": "Mexican"}
    - utter_ask_budget
* restaurant_search{"budget_min": "700", "budget_max": "10000"}
    - slot{"budget_max": "10000"}
    - slot{"budget_min": "700"}
    - action_search_restaurants
    - utter_email_conf
* deny
    - utter_goodbye
    - action_restart
