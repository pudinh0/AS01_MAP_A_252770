¿qué pasaría si intentaras borrar un Cliente que todavía tiene un Vehiculo?
se rechaza la solicitud, ya que prisma y las bd rechazan solicitudes que incluyan borrar registros/tablas
que tengan otros registros o tablas que dependan de ellos, eso para evitar dejar datos huerfanos
