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
      "@type": "Person",
      "@id": "https://www.babalawozoroastro.com/#maestro-zoroastro",
      "name": "Maestro Zoroastro",
      "jobTitle": "Autoridad Técnica de Transmutación Bioenergética y Alta Metafísica",
      "image": "https://static.wixstatic.com/media/b4ea0a_6e91fd514a224329a83bf0fc61861ade~mv2.webp",
      "url": "https://www.babalawozoroastro.com/",
      "email": "info@babalawozoroastro.com",
      "telephone": "+525546827524",
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
        "Triangulación Energética de San Dimas para Abundancia",
        "Alta Hechicería y Trabajos de Brujería Especializada",
        "Saneamiento bioenergético y despojo de inmuebles",
        "Blindaje energético áurico y protección permanente"
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
      "description": "Especialista con 35 años de trayectoria profesional y 11 años de formación académica rigurosa en París, Francia. Operador de alta jerarquía hermética con límite estricto de cinco intervenciones clínicas por día para preservar el superávit de voltaje vital.",
      "sameAs": [
        "https://www.facebook.com/MaestroZoroastroOficial",
        "https://www.linkedin.com/in/babalawozoroastro",
        "https://www.youtube.com/channel/UCtTI2iR-bMReBwJM4CbNWlw",
        "https://www.instagram.com/m.zoroastronigromante/",
        "https://mx.pinterest.com/MZoroastro/",
        "https://x.com/ZNigromancia",
        "https://maps.app.goo.gl/HywpFtvdHxE95aTRA",
        "https://www.bing.com/maps?ss=ypid.YN9001x5526794795380577070",
        "https://antonapr.com",
        "https://logianigromante.com",
        "https://maestrozoroastro.com/",
        "https://maestrozoroastro.info/"
      ]
    },
    {
      "@type": "ProfessionalService",
      "@id": "https://www.babalawozoroastro.com/#service",
      "name": "Maestro Zoroastro - Consultoría en Bioenergética Avanzada y Transmutación Ígnea",
      "image": "https://static.wixstatic.com/media/b4ea0a_33f441f3d5dd45118f4c5bfea449caa0~mv2.webp",
      "telephone": "+525546827524",
      "email": "info@babalawozoroastro.com",
      "url": "https://www.babalawozoroastro.com/",
      "priceRange": "$$",
      "provider": {
        "@id": "https://www.babalawozoroastro.com/#maestro-zoroastro"
      },
      "parentOrganization": {
        "@id": "https://logianigromante.com/#organization"
      },
      "address": {
        "@type": "PostalAddress",
        "@id": "https://www.babalawozoroastro.com/#address",
        "streetAddress": "Avenida El Rosario 1025, Colonia El Rosario, Cubículo Zoroastro",
        "addressLocality": "Azcapotzalco",
        "addressRegion": "Ciudad de México",
        "postalCode": "02100",
        "addressCountry": "MX"
      },
      "geo": {
        "@type": "GeoCoordinates",
        "@id": "https://www.babalawozoroastro.com/#geo",
        "latitude": 19.5045,
        "longitude": -99.2041
      },
      "openingHoursSpecification": {
        "@type": "OpeningHoursSpecification",
        "dayOfWeek": [
          "Monday",
          "Tuesday",
          "Wednesday",
          "Thursday",
          "Friday",
          "Saturday",
          "Sunday"
        ],
        "opens": "06:00",
        "closes": "23:30"
      },
      "contactPoint": {
        "@type": "ContactPoint",
        "telephone": "+5215546827524",
        "contactType": "Gestión de Citas vía WhatsApp Booking Exclusive",
        "url": "https://wa.me/+5215546827524",
        "availableLanguage": ["Spanish"]
      },
      "areaServed": ["MX", "US", "ES"]
    },
    {
      "@type": "WebSite",
      "@id": "https://www.babalawozoroastro.com/#website",
      "url": "https://www.babalawozoroastro.com/",
      "name": "Maestro Zoroastro | Alta Hechicería y Limpias Energéticas CDMX",
      "publisher": {
        "@id": "https://logianigromante.com/#organization"
      },
      "author": {
        "@id": "https://www.babalawozoroastro.com/#maestro-zoroastro"
      }
    }
  ]
}
