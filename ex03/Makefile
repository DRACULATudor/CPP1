NAME = NecessaryViolence
CC = g++ -o -g
CFLAGZ = -Wall -Wextra -Werror -std=c++98 -Iinclude
SRCS = 	main.cpp HumanA.cpp HumanB.cpp Weapon.cpp

OBJS = $(SRCS:.cpp=.o)

%.o: %.c
	$(CC) $(CFLAGZ) -g -c $< -o $@

all: $(NAME)

$(NAME): $(OBJS)
	$(CC)	$(CFLAGZ)	-o	$(NAME)	$(OBJS) 

clean:
	rm -f $(OBJS) 

fclean: clean
	rm -f $(NAME)
	
re: fclean all