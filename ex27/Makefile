# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: sfernand <sfernand@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/07 13:04:00 by sfernand          #+#    #+#              #
#    Updated: 2018/11/07 13:04:07 by sfernand         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = ft_display_file
FLAFS = -Wall -Werror -Wextra
SRC = ./srcs/*.c
HD = ./includes/

all: $(NAME)

$(NAME):
	gcc $(FLAGS) $(SRC) -I $(HD) -o $(NAME)

clean:
	rm -f *.o

fclean: clean
	rm -f $(NAME)

re: fclean all
