- As a customer, so I can receive my tickets, I want to provide my contact information.
- As a customer, so I can decide which movie I want to watch, I want to see a list of movies.
- As an admin, so I can manage the movies shown at the cinema, I want to update the list of movies.

  Customer Table

  Customer ID FirstName LastName Street City Phone eMail createdAt updatedAt

  30001 Alice Peters 23 Second California 777 a@b.com 22/02/222 22/02/222
  30002 John Whine 45 Lane JHB 444 b@c.com 22/02/222 22/02/222
  30004 David Plimoff 12 Groto JHB 333 d@e.com 22/02/222 22/02/222
  30005 Fred Starow 55 Deans Californiia 222 t@v.com 22/02/222 22/02/222
  Purchase Order Table
  OrderNumber Customer ID CustomerName Paid DateSent eMail CreatedAt UpdatedAt movie screen startTime

  # 85408 30001 Alice Peters TRUE 23/11/2222 a@b.com 22/02/222 22/02/222

  # 76540 30002 John Whine TRUE 23/11/2222 z@w.com 22/02/222 22/02/222

  # 64097 30002 John Whine TRUE 23/11/2222 z@w.com 22/02/222 22/02/222

  # 76309 30001 Alice Peters TRUE 23/11/2222 a@b.com 22/02/222 22/02/222

      	Movie Table
      Movie ID	Movie Name	Duration	Rating / 10
      # M 80000	Donnie Darko	01:45	9,5
      # M80001	Possessed	02:23	7,5
      # M80002	The Gathering	01:59	4,0



      	Screenings Table
      Cine	Date	Time	Movie
      Screen 1	22/03/2022	10:00	# M 80000
      Screen 1	22/03/2022	12:00	# M 80000
      Screen 1	22/03/2022	19:00	# M 80000
      Screen 2	01/12/2022	10:00	# M80002
      Screen 2	01/12/2022	12:00	# M80002
      Screen 2	01/12/2022	19:00	# M80000

nouns verbs
cinema see movies shown on various screens at various times
customer
various screens
tickets book tickets, ordered online, delivered by email
movie list show updated movie list to customers
screen
cinema wants to keep record of purchases and movies seen
As a business we want to keep records of our customers and what movies they have seen
As a customer I want to order tickets online and have them delivered by email.
As a customer I want the cinema to keep my details so I do not have to enter them again
As a customer I want proof of purchase in the form of a purchase order
As a customer I want a ticket with allrelevent details
