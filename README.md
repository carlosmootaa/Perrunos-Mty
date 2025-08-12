import React from 'react';
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";

export default function PerrunosMty() {
  return (
    <div className="bg-white text-gray-900">
      {/* WhatsApp Button at the top */}
      <div className="fixed top-4 right-4 z-50">
        <a
          href="https://wa.me/528111833287"
          target="_blank"
          rel="noopener noreferrer"
        >
          <Button className="bg-green-500 hover:bg-green-600 text-white text-lg p-4 rounded-full shadow-lg">
            💬 WhatsApp
          </Button>
        </a>
      </div>

      {/* Hero Section */}
      <section className="text-center py-20 bg-gradient-to-r from-yellow-300 to-orange-400">
        <h1 className="text-5xl font-bold">Perrunos Monterrey</h1>
        <p className="mt-4 text-xl">Cuidado y amor para tu mejor amigo 🐾</p>
      </section>

      {/* Reviews Section */}
      <section className="py-16 bg-gray-100">
        <h2 className="text-3xl font-bold text-center mb-8">Reseñas</h2>
        <div className="max-w-4xl mx-auto grid gap-6 md:grid-cols-2">
          <Card>
            <CardContent className="p-6">
              <p className="italic">“Carlos es increíble, cuida a mi perro como si fuera suyo.”</p>
              <p className="mt-4 font-bold">- Cliente Feliz</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6">
              <p className="italic">“Servicio confiable y con mucho cariño para los perritos.”</p>
              <p className="mt-4 font-bold">- Amante de los Animales</p>
            </CardContent>
          </Card>
        </div>
      </section>

      {/* Contact Info */}
      <footer className="py-8 bg-gray-900 text-white text-center">
        <p>📧 Correo: carlos.motah@hotmail.com</p>
        <p>📱 Número: 8111833287</p>
        <p>📘 Facebook: <a href="https://www.facebook.com/share/16kabaja7Y/?mibextid=wwXlfr" className="text-blue-400 underline">Perrunos Monterrey</a></p>
      </footer>
    </div>
  );
}
