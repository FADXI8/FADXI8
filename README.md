// Fadxi Book Store - App without Payment Integration import React from 'react'; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

const books = [ { title: "Buugga Koowaad", author: "Qoraa La Yaqaan", type: "PDF", description: "Buuggani waa mid dijital ah oo lagu akhrisan karo online.", fileUrl: "#" }, { title: "Buugga Labaad", author: "Qoraa Kale", type: "Physical", description: "Buuggani waa la taaban karo. Fadlan nala soo xiriir si aad u iibsato.", contact: "+25261xxxxxxx" } ];

export default function BookStore() { return ( 

Fadxi Book Store {books.map((book, index) => ( {book.title} 

Qoraa: {book.author}

{book.description}

{book.type === "PDF" ? ( Akhri Buugga (PDF) ) : ( 

La xiriir: {book.contact}

)} ))} 

); } 
