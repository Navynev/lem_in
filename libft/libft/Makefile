# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: jbrisset <jbrisset@student.42.fr>          +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/11/07 09:30:22 by jbrisset          #+#    #+#              #
#    Updated: 2019/02/22 15:20:03 by ndelhomm         ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

NAME = libft.a
SRCS = ft_isdigit.c ft_lstmap.c ft_memdel.c ft_putnbr.c ft_strcmp.c\
ft_strjoin.c ft_strncpy.c ft_strstr.c ft_isprint.c\
ft_lstnew.c ft_memmove.c ft_putnbr_fd.c ft_strcpy.c ft_strlcat.c ft_strndup.c\
ft_strsub.c ft_atoi.c ft_itoa.c ft_memalloc.c ft_memset.c\
ft_putstr.c ft_strdel.c ft_strlen.c ft_strnequ.c ft_strtrim.c\
ft_bzero.c ft_lstadd.c ft_memccpy.c ft_putchar.c ft_putstr_fd.c\
ft_strdup.c ft_strmap.c ft_strnew.c ft_tolower.c ft_isalnum.c\
ft_lstdel.c ft_memchr.c ft_putchar_fd.c ft_strcat.c ft_strequ.c\
ft_strmapi.c ft_strnstr.c ft_toupper.c ft_isalpha.c ft_lstdelone.c\
ft_memcmp.c ft_putendl.c ft_strchr.c ft_strnchr.c ft_striter.c ft_strncat.c\
ft_strrchr.c ft_isascii.c ft_lstiter.c ft_memcpy.c ft_putendl_fd.c\
ft_strclr.c ft_striteri.c ft_strncmp.c ft_strsplit.c\
ft_islower.c ft_isupper.c ft_isspace.c ft_isxdigit.c\
ft_intlen.c get_next_line.c ft_intlen_base.c ft_uintlen_base.c\
ft_abs.c ft_itoa_base.c ft_uitoa_base.c ft_swap.c ft_is_nb.c\
count_char.c ft_round.c ft_round_up.c\

HEADERS = libft.h
OBJECTS = $(SRCS:%.c=%.o)
FLAGS = -Wall -Werror -Wextra

all: $(NAME)

$(NAME): $(OBJECTS)
	@gcc $(FLAGS) -c $(SRCS) -I $(HEADERS)
	@ar rc $(NAME) $(OBJECTS)

clean:
	@/bin/rm -f $(OBJECTS)

fclean: clean
	@/bin/rm -f $(NAME)

re: fclean all
