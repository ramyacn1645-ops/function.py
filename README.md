# function.py
def make_sandwich(bread_type,filling,cheese=None,toasted = False):
    if toasted:
        toast_text = "toasted"
    else:
        toast_text =""
    if cheese:
        return f'Making {toast_text} {bread_type} sandwich with {filling} and {cheese} cheese.'
    else:
        return f'Making {toast_text} {bread_type} sandwich with {filling}.'
customer1 = make_sandwich("wheat","tureky","chaddar",True)
print(customer1)
