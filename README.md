// Fadxi Book Store - App without Payment Integration # Fadxi Book Store

**Fadxi Book Store** is a simple app where you can list and sell PDF and physical books.  
Created by Fadxi Carab, a 17-year-old youth entrepreneur encouraging reading and book exchange.

## App Features:
- **PDF Books**: Digital books available for online reading or download.
- **Physical Books**: Hard copy books available through direct contact.
- **Admin Upload Only**: Only the admin can upload or list books.

## Upcoming Features:
- In-app reading space for PDFs.
- A marketplace section for exchanging books between users.
- Rewards for users who read and return books.

---

**Contact:** fadxibookstore@example.com from "@/components/ui/card"; import { Button } from "@/components/ui/button";

const books = [ { title: "Buugga Koowaad", author: "Qoraa La Yaqaan", type: "PDF", description: "Buuggani waa mid dijital ah oo lagu akhrisan karo online.", fileUrl: "#" }, { title: "Buugga Labaad", author: "Qoraa Kale", type: "Physical", description: "Buuggani waa la taaban karo. Fadlan nala soo xiriir si aad u iibsato.", contact: "+25261xxxxxxx" } ];

export default function BookStore() { return ( 

Fadxi Book Store {books.map((book, index) => ( {book.title} 

Qoraa: {book.author}

{book.description}

{book.type === "PDF" ? ( Akhri Buugga (PDF) ) : ( 

La xiriir: {book.contact}

)} ))} 

); } 
Update README with proper description
