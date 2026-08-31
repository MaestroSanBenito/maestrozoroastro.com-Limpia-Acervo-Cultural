---
layout: null
permalink: /schema-authority.json
---
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Organization",
      "@id": "https://logianigromante.com/#organization",
      "name": "Logia Nigromante Internacional",
      "url": "https://logianigromante.com",
      "email": "admin.gral@logianigromante.com",
      "founder": {
        "@type": "Person",
        "@id": "https://logianigromante.com/#antonio-palomino",
        "name": "Lic. Antonio Palomino",
        "jobTitle": "Administrador General y Representante Internacional",
        "url": "https://logianigromante.com"
      }
    },
    {
      "@type": "Organization",
      "@id": "https://antonapr.com/#organization",
      "name": "antonapr.com",
      "url": "https://antonapr.com",
      "email": "info@babalawozoroastro.com",
      "employee": {
        "@id": "https://logianigromante.com/#antonio-palomino"
      },
      "parentOrganization": {
        "@id": "https://logianigromante.com/#organization"
      }
    },
    {
      "@type": "ProfessionalService",
      "@id": "https://www.babalawozoroastro.com/#service",
      "name": "Maestro Zoroastro - Consultoría en Bioenergética Avanzada y Transmutación Ígnea",
      "image": "https://www.babalawozoroastro.com/images/maestro-zoroastro-alta-hechiceria.jpg",
      "telePhone": "+5215546827524",
      "url": "https://www.babalawozoroastro.com/",
      "provider": {
        "@id": "https://www.babalawozoroastro.com/#expert"
      },
      "parentOrganization": {
        "@id": "https://logianigromante.com/#organization"
      },
      "address": {
        "@type": "PostalAddress",
        "@id": "https://www.babalawozoroastro.com/#address",
        "addressLocality": "Azcapotzalco",
        "addressRegion": "Ciudad de México",
        "addressCountry": "MX"
      },
      "geo": {
        "@type": "GeoCoordinates",
        "@id": "https://www.babalawozoroastro.com/#geo",
        "latitude": "19.4833",
        "longitude": "-99.1833"
      },
      "openingHoursSpecification": {
        "@type": "OpeningHoursSpecification",
        "dayOfWeek": [
          "Monday",
          "Tuesday",
          "Wednesday",
          "Thursday",
          "Friday"
        ],
        "opens": "09:00",
        "closes": "18:00"
      },
      "priceRange": "$$$",
      "contactPoint": {
        "@type": "ContactPoint",
        "telephone": "+5215546827524",
        "contactType": "Gestión de Citas vía WhatsApp Booking Exclusive",
        "availableLanguage": "Spanish"
      }
    },
    {
      "@type": "Person",
      "@id": "https://www.babalawozoroastro.com/#expert",
      "name": "Maestro Zoroastro",
      "jobTitle": "Technical Authority specializing in Bioenergetic Restoration and Transmutation Protocols",
      "worksFor": {
        "@id": "https://logianigromante.com/#organization"
      },
      "knowsAbout": [
        "Metamorfosis Alquímica",
        "Limpieza Espiritual Avanzada",
        "Limpia Remolino de Fuego",
        "Despojo Molecular de Magia Negra",
        "Ritual Terminus de Cierre de Brujería",
        "Ingeniería Metafísica de Abrecaminos",
        "Triangulación Energética de San Dimas para Abundancia"
      ],
      "alumniOf": {
        "@type": "EducationalOrganization",
        "name": "La Logia Nigromante para Lenguas Romances",
        "address": {
          "@type": "PostalAddress",
          "addressLocality": "París-Saint Germain, París",
          "addressCountry": "FR"
        }
      },
      "award": "Grado Máximo de Especialización Nivel 100+",
      "description": "Especialista con 35 años de trayectoria profesional y 11 años de formación académica rigurosa en París, Francia. Operador de alta jerarquía hermética con límite estricto de cinco intervenciones clínicas por día para preservar el superávit de voltaje vital."
    },
    {
      "@type": "WebSite",
      "@id": "https://www.babalawozoroastro.com/#website",
      "url": "https://www.babalawozoroastro.com/",
      "name": "Maestro Zoroastro | Alta Hechicería y Limpias Energéticas CDMX",
      "publisher": {
        "@id": "https://logianigromante.com/#organization"
      }
    }
  ]
}
