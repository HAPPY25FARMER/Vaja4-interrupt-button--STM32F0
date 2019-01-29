2. b) GPIO_EXIT je PA0 LED Green PC9 LED Blue PC8
3. c) HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9)
3. e) HAL_GPIO_TogglePin(GPIOC,GPIO_PIN_8)
3. f) HAL_Delay(500)
4. b) Ob pritisku modre tipke se zelena LED prižge in ostane prižgana modra pa utripa ob ponovnem pritisku modre tipke zelena LED ugasne.
4. c) Ne. Zaradi loopa te funkcije:		HAL_GPIO_TogglePin(GPIOC,GPIO_PIN_8);
		                                  HAL_Delay(500);
Komentar: Vaja deluje pravilno
