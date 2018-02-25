# Create sort_contacts function
def sort_contacts(contacts):
    sorted_contacts = []
    for k, [p, e] in sorted(contacts.items()):
        sorted_contacts.extend([(k, p, e)])
    return sorted_contacts

def main():
    contacts = {"Horney, Karen": ("1-541-656-3010", "karen@psychoanalysis.com"),
                "Welles, Orson": ("1-312-720-8888", "orson@notlive.com"),
                "Freud, Anna": ("1-541-754-3010", "anna@psychoanalysis.com")}
    print(sort_contacts(contacts))
main()
    

# The code below is just for your testing purposes. Make sure you pass all the tests.
# In Vocareum, only put code for the sort_contacts function above
from test import testEqual

testEqual(sort_contacts({"Horney, Karen": ("1-541-656-3010", "karen@psychoanalysis.com"),
        "Welles, Orson": ("1-312-720-8888", "orson@notlive.com"),
        "Freud, Anna": ("1-541-754-3010", "anna@psychoanalysis.com")}), [('Freud, Anna', '1-541-754-3010',
        'anna@psychoanalysis.com'), ('Horney, Karen', '1-541-656-3010', 'karen@psychoanalysis.com'),
        ('Welles, Orson', '1-312-720-8888', 'orson@notlive.com')])
testEqual(sort_contacts({"Summitt, Pat": ("1-865-355-4320", "pat@greatcoaches.com"),
    "Rudolph, Wilma": ("1-410-5313-584", "wilma@olympians.com")}),
    [('Rudolph, Wilma', '1-410-5313-584', 'wilma@olympians.com'),
    ('Summitt, Pat', '1-865-355-4320', 'pat@greatcoaches.com')])
testEqual(sort_contacts({"Dinesen, Isak": ("1-718-939-2548", "isak@storytellers.com")}),
    [('Dinesen, Isak', '1-718-939-2548', 'isak@storytellers.com')])
testEqual(sort_contacts({"Rimbaud, Arthur": ("1-636-555-5555", "arthur@notlive.com"),
    "Swinton, Tilda": ("1-917-222-2222", "tilda@greatActors.com"),
    "Almodovar, Pedro": ("1-990-622-3892", "pedro@filmbuffs.com"), "Kandinsky, Wassily":
    ("1-333-555-9999", "kandinsky@painters.com")}), [('Almodovar, Pedro', '1-990-622-3892',
    'pedro@filmbuffs.com'), ('Kandinsky, Wassily', '1-333-555-9999', 'kandinsky@painters.com'),
    ('Rimbaud, Arthur', '1-636-555-5555', 'arthur@notlive.com'), ('Swinton, Tilda',
    '1-917-222-2222', 'tilda@greatActors.com')])
