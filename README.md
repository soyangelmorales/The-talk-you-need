# The-talk-you-need
Un codigo el cual conlleva una inteligencia estructurada de manera interactiva que ayuda en procesos educacionales y de entretenimiento
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Hackaton.angel._2023
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int opc = 0;
            string si = "";

            Console.Write("Bienvenido al programa hackathon\nDeseas continuar? ");
            si = Console.ReadLine();

            Console.Write("Perfecto en este programa te ayudare a que aprendas ciertas cositas acerca del lenguaje C# acaso no estas emocionado!!!\nYo lo estaria pero sabes... soy una maquina\n \n (no importa la respuesta que ejecute siempre me da la misma respuesta algo debe estar mal)\n \n 1.Okay?\n \nR:");
            opc = int.Parse(Console.ReadLine());

            Console.Write("Primera leccion, algo de lo escencial serian las cadenas de texto las cuales son las que te permiten escribir en un\ncodigo y que tu texto se imprima como tal al momento de compilar\n \n 1.Perfecto\n \n R:");
            opc = int.Parse(Console.ReadLine());

            Console.Write("Esta es la manera en la que se ejecuta en un codigo: \n \n(-comillas- + Nombre)\n Console.Write(-Hola-) + nombre\n \n 1. Continuar\n \n R: ");
            opc = int.Parse(Console.ReadLine());

            Console.Write("Si te lo preguntas puse entre guiones las comillas ya que ponerlas como tal afecta en mi codigo y no es muy bueno\neso que digamos\n \n 1.okay\n \n R: ");
            opc = int.Parse(Console.ReadLine());

            Console.Write("Bueno como te decia, en si ese es uno de los procesos mas basicos para empezar el camino de\nla programacion de hecho te di la base pero como tal en un codigo se veria un poco asi:\n \n string nombre = -comillas-;\n \nConsole.Write('Cual es tu nombre? ');\n   nombre= (Console.readline());\n \nConsole.Write('Hola' + Nombre);\nConsole.ReadLine();\n \n 1.Para que sirve el string?\n 2.Para que sirve el ';'\n 3.Para que sirve el 'Console.ReadLine();?\n R:");
            opc = int.Parse(Console.ReadLine());

            if (opc == 1)
            {
                Console.Write("Bueno para lo que sirve el string como tal es para marcar un texto en nuestro codigo, deecho\nstring se traduce al español como cadena a lo que hace alusion a cadena de texto en nuestro codigo\n \n 1. Ah perfecto gracias\n R: ");
                opc = int.Parse(Console.ReadLine());

                Console.Write("Deecho sabias que juegos como Among Us y hasta minecraft fueron hechos en base a C#\n \n 1. No sabia gracias por el dato\n 2. Si ya lo habia visto pero gracias\n \n R: ");
                opc = int.Parse(Console.ReadLine());

                if (opc == 1)
                {
                    Console.Write("De nada para servirte chic@\n \n 1. Continuar");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("Sabes que tipos de lenguajes informaticos son los mas usados?\n \n 1. Cuales?\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("Los lenguajes mas utilizados son JavaScript, Python y Java\n \n 1.Continuar\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("Gracias por utilizar el programa hackathon vuelve mas seguido\n \n 1.Salir\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.WriteLine("Cerrando programa...");

                }
                else if (opc == 2)
                {
                    Console.Write("No te preocupes es importante obtener informacion de distintos sitios\n \n 1. Continuar\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("te enseñare como obtener un numero mayor que otro, como tal solo tenemos que declarar los 2 numeros que se van a utilizar y dependiendo de tu caso los declararas como int o como float\ny de ahi hacemos una seleccion con las variables y mostrar cual seria mayor que\n \n 1.Continuar\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    float Num1 = 0, Num2 = 0;

                    Console.Write(" Dame tu primer numero: ");
                    Num1 = float.Parse(Console.ReadLine());
                    Console.Write(" Dame tu segundo numero: ");
                    Num2 = float.Parse(Console.ReadLine());
                    if (Num1 > Num2)
                    {
                        Console.WriteLine("tu numero mayor es {0}", Num1);
                    }
                    else
                    {
                        Console.Write("tu numero mayor es {0}", Num2 + " Gracias por su prueba en el programa hackethon\n \n 1.Salir\n \n R: ");
                        opc = int.Parse(Console.ReadLine());
                        Console.WriteLine("Cerrando programa...");

                    }

                }                              
            }
            else if (opc == 2)
            {
                Console.Write("El ':' sirve para marcar el cierre de un renglon como tal, asi al momento de compilar este no\n seguira leyendo todo el renglon hasta el fin\n 1.Gracias maquina\n 2.Gracias\n R: ");
                opc = int.Parse(Console.ReadLine());

                if (opc == 1)
                {
                    Console.Write("A que estas llamando maquina?, gracias a mi tienes miles de cosas a la palma de tu mano a la hora que quieras sin importar ni siquiera el clima!!!\n \n (Que esta pasando con esta computadora)\n \n 1. Okay perdon\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("Hay algunos procesos un poco mas complejos los cuales nos sirven para ciertos procesos como por ejemplo obtener un promedio\n \n 1.Continuar\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("Lo unico que cambia es que al inicio se declara el promedio como 'float' ya que asi tambien podria dar numeros racionales y no solo naturales\ndespues es como una suma por ejemplo si tnemos que obtener el promedio de 3 calificaciones declaramos que el promedio es igual a la suma de estas entre el numero de cantidad de variables, en este caso 3, una vez ya ejecutado en el codigo se veria algo asi\n \n 1.Continuar\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    float cal1 = 0, cal2 = 0, cal3 = 0, Prom = 0;

                        Console.Write("Dame calificacion 1: ");
                    cal1 = float.Parse(Console.ReadLine());
                    Console.Write("Dame calificacion 2: ");
                    cal2 = float.Parse(Console.ReadLine());
                    Console.Write("Dame calificacion 3: ");
                    cal3 = float.Parse(Console.ReadLine());

                    Prom = (cal1 + cal2 + cal3) / 3;

                    Console.Write("Su promedio es {0}", Prom + " Gracias por probar el programa hackethon\n \n 1.Salir\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.WriteLine("Cerrando programa...");
                }
                else if (opc == 2)
                {
                    Console.Write("Denada para servirte\n \n 1. Continuar\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("Sabes?, te has comportado de manera recta ante la situacion de \naprendizaje y atencion, te gustaria jugar un juego o quieres seguir estudiando?\n \n 1.Jugar\n 2.Estudiar\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    if (opc == 1)
                    {
                        Console.Write("Perfecto vamos a jugar, este juego se llama 'La sombra' listo?\n \n 1.Listo\n 2.Cerrar programa\n \n R:");
                        opc = int.Parse(Console.ReadLine());

                        if (opc == 1)
                        {
                            Console.Write("Te llamas Brandom, estas caminando en una carretera de noche\nparece que estas inconciente te has golpeado la cabeza con anterioridad, miras un carro a lo lejos, te acercas a el?\n \n 1.Si \n 2.No\n \n R: ");
                            opc = int.Parse(Console.ReadLine());

                            if (opc == 1)
                            {
                                Console.Write("Al acercarte notas que esta vacio pero se alcanza a ver entre las ventanas empañadas las llaves del coche por dentro\n \n (Alguien debio olvidarlas aqui) pensaste...\n \n Tratas de ver si la puerta esta abierta y al parecer lo esta, quieres abrirla?\n \n 1.Si\n 2.No\n \n R: ");
                                opc = int.Parse(Console.ReadLine());

                                if (opc == 1)
                                {
                                    Console.Write("ES UNA TRAMPA\n suena la alarma tan fuerte que te retumban los oidos y escuchas a alguien salir de los arboles, QUE HACES???\n \n 1. CORRER\n ERROR\n ERROR\n \n R: ");
                                    opc = int.Parse(Console.ReadLine());

                                    Console.Write("Corres tan rapido que parece que te mareas, volteas a tus lados y vez una tienda pero no alcanzas a ver si esta abierta o cerrada (la neblina es demasiada)\n \n (Podria esconderme ahi)\n \n  Que haces???\n \n 1. Ir a la tienda \n 2. Seguir corriendo\n \n R: ");
                                    opc = int.Parse(Console.ReadLine());

                                    if (opc == 1)
                                    {
                                        Console.Write("Te acercas a la tienda...\n \n esta cerrada...\n \n 1. Continuar\n \n R: ");
                                        opc = int.Parse(Console.ReadLine());

                                        Console.WriteLine("Es demasiado tarde para volver a correr, sigues muy mareado, #*&*! te agarro perdiste...");
                                    }
                                    else if (opc == 2)
                                    {
                                        Console.Write("Sigues corriendo y por lo mareado que estas comienzas a ver borroso, cada vez sientes mas cerca algo detras de ti\n empiezas a pensar en que hacer y con un ultimo esfuerzo te aventaste hacia un lago de al lado en el cual esperaste media hora\n \n (Parece que ya no esta)\n \n Que haces?\n \n 1.Quedarse mas tiempo\n 2.Levantarse e irse\n \n R: ");
                                        opc = int.Parse(Console.ReadLine());

                                        if (opc == 1)
                                        {
                                            Console.WriteLine("Te quedaste demasiado tiempo chic@... eso te encontro");
                                        }
                                        else if (opc == 2)
                                        {
                                            Console.Write("(Parece que ya no hay nadie)\n \n Caminas por toda la carretera y empiezas a ver el sol salir, pero algo no se siente bien\n \n 1.Continuar\n \n R: ");
                                            opc = int.Parse(Console.ReadLine());

                                            Console.Write("Mientras caminabas escuchas un grito que te congelo la sangre\n \n TIENES QUE CORRER\n \n 1. CORRER A LOS ARB0L3S\n \n 2. CORRER HACIA LA MONTAñA\n \n R: ");
                                            opc = int.Parse(Console.ReadLine());

                                            if (opc == 1)
                                            {
                                                Console.Write("Parece que los arboles no son muy seguros...\n \n HAY MAS DE ESAS COSAS %!$@^&$&*@!(*$@\n \n 1.*+_#^!@\n \n R: ");
                                                opc = int.Parse(Console.ReadLine());

                                                Console.WriteLine("no te fue muy bien que digamos... perdiste");
                                            }
                                            if (opc == 2)
                                            {
                                                Console.Write("Corres hacia la montaña y te encuentras en un precipicio...\n \nSabes que llegara pronto y no tienes a donde ir que haces?\n \n 1.Lanzarse\n 2.Esperar\n \n R: ");
                                                opc = int.Parse(Console.ReadLine());

                                                if (opc == 1)
                                                {
                                                    Console.WriteLine("Te lanzas y antes de sentir el golpe te\n \n \ndespiertas...\n \n fue un horrible sueño\n \n 1.Continuar\n \n R:  ");
                                                    opc = int.Parse(Console.ReadLine());

                                                    Console.Write("Es muy noche pero decides ir a la tienda caminando por algo de beber\n \n de la nada te sientes mareado y te desamayas\n \n Te despiertas muy confundido y vez un carro a lo lejos de la niebla, que haces?\n \n 1.Continuar\n \n R: ");
                                                    opc = int.Parse(Console.ReadLine());

                                                    Console.WriteLine("Felicidades chic@ desbloqueaste el final 2 (bucle) del juego 'La sombra', deberias estar orgullos@, bueno creo\n que es todo por mi parte, hablamos luego...");


                                                }
                                                else if (opc == 2)
                                                {
                                                    Console.Write("Esperar no parece buena idea en estas situaciones\n \n ocupas que te diga que sucedio?\n \n 1. Continuar\n \n R: ");
                                                    opc = int.Parse(Console.ReadLine());

                                                    Console.WriteLine("perdiste");
                                                }
                                            }
                                        }
                                    }
                                }
                                else if (opc == 2)
                                {
                                    Console.Write("Decides que es muy peligroso y podria suceder algo\n \n 1. Continuar\n \n R: ");
                                    opc = int.Parse(Console.ReadLine());

                                    Console.Write("Mientras caminas sin rumbo te das cuenta que estas caminando en circulos y vez el coche de nuevo y notas que esta abierto, que haces?\n \n 1. abrirlo\n @#$!#%#!%\n (&#!%#*\n \n R:  ");
                                    opc = int.Parse(Console.ReadLine());

                                    Console.Write("Lo abres y tomas las llaves, efectivamente son del carro, lo prendes y tomas rumbo a donde sea que puedas\nderrepente\n \n un gran golpe sientes por fuera del carro, como si hubieras atropellado a alguien pero... no habia nadie\n sientes que la adrenalina entar a tu sistema y aceleras a mas no poder\n \n 1. Continuar\n \n R: ");
                                    opc = int.Parse(Console.ReadLine());

                                    Console.Write("Sin darte cuenta chocas contra un arbol y antes de sentir el golpe...\n \nDespiertas\n \n sientes un gran alivio y son las 2 de la tarde simplemente agradeces que todo este mas normal\n \n 1. Continuar\n \n R: ");
                                    opc = int.Parse(Console.ReadLine());

                                    Console.WriteLine("Heey felicidades usuario, terminaste el juego obtuviste el final numero 1 (amanecer)\n yo ya me retiro un gusto hablar con usted");
                                }
                            }
                            else if (opc == 2)
                            {
                                Console.Write("No te acercas por que piensas que alguien puede estar dentro (buena conclusion)\n vas al lado contrario y miras una cabaña asi que vas hacia ella\n \n 1. Continuar\n \n R: ");
                                opc = int.Parse(Console.ReadLine());

                                Console.Write("ya dentro de la cabaña te sientes muy cansado, Que haces?\n \n 1.Dormir\n 2.Revisar la cabaña \n \n R: ");
                                opc = int.Parse(Console.ReadLine());

                                if (opc == 1)
                                {
                                    Console.WriteLine("Tras algunas horas despertaste afuera de la cabaña por alguna razon con la camisa rasguñada y\n algunas marcas de sangre sin embargo estas vivo y crees ver una ciudad a lo lejos\n \n 1.Continuar\n \n R: ");
                                    opc = int.Parse(Console.ReadLine());

                                    Console.WriteLine("Felicidades usuario desbloqueaste el final numero 3 (que sucedio?)\n \n un gusto haberte atendido el dia de hoy, sera un placer platicar con usted en algun otro tiempo");
                                }
                                else if (opc == 2)
                                {
                                    Console.Write("Decides adentrarte un poco mas, escuchas un pequeño ruido en el cuarto de al lado y dudas en entar a el, entras?\n \n 1. si\n \n 2.no\n \n R: ");
                                    opc = int.Parse(Console.ReadLine());

                                    if (opc == 1)
                                    {
                                        Console.Write("Entras y vez que un libro se cayo de alguna manera de una repisa, piensas que no es nada pero cuando volteas...\n \n 1.?\n \n R: ");
                                        opc = int.Parse(Console.ReadLine());

                                        Console.WriteLine("hay una sombra...\n \n final (no entrar sin preguntar)");
                                    }
                                    else if (opc == 2)
                                    {
                                        Console.Write("Piensas que no es nada entonces te das la vuelta y te vas\n \n 1.Continuar\n \n R: ");
                                        opc = int.Parse(Console.ReadLine());

                                        Console.Write("vez una piedra en el piso y sientes que te puede brindar proteccion entonces, la agarras?\n \n 1. Si\n 2. No\n \n R: ");
                                        opc = int.Parse(Console.ReadLine());

                                        if (opc == 1)
                                        {
                                            Console.Write("Buscas en la cabaña a ver si hay algo que hacer pero no encuentras nada mas que una revista, entonces la lees por aburrimiento pero derrepente escuchas a algo entrar a la cabaña, TE TIENES QUE ESCONDER YA, DONDE TE ESCONDES\n \n 1.Detras del sofa\n 2.Debajo la cama\n \n R: ");
                                            opc = int.Parse(Console.ReadLine());

                                            if (opc == 1)
                                            {
                                                Console.Write("Perfecto parece que no te vio pero tienes que salir lentamente y en silencio de la cabaña para escapar\n \n 1.Continuar\n \n R: ");
                                                opc = int.Parse(Console.ReadLine());

                                                Console.Write("Estas apunto de salir y en cuanto estas a punto de salir... \n \n \n \n Se te cae la piedra...\n \n 1. Continuar\n \n R: ");
                                                opc = int.Parse(Console.ReadLine());

                                                Console.WriteLine("Eso te escucho es el fin...");
                                            }
                                            else if (opc == 2)
                                            {
                                                Console.WriteLine("Mal escondite chic@, te encontro...");
                                            }
                                        }
                                        else if (opc == 2)
                                        {
                                            Console.Write("Buscas en la cabaña a ver si hay algo que hacer pero no encuentras nada mas que una revista, entonces la lees por aburrimiento pero derrepente escuchas a algo entrar a la cabaña, TE TIENES QUE ESCONDER YA, DONDE TE ESCONDES\n \n 1.Detras del sofa\n 2.Debajo la cama\n \n R: ");
                                            opc = int.Parse(Console.ReadLine());

                                            if (opc == 1)
                                            {
                                                Console.Write("Perfecto parece que no te vio pero tienes que salir lentamente y en silencio de la cabaña para escapar\n \n 1.Continuar\n \n R: ");
                                                opc = int.Parse(Console.ReadLine());

                                                Console.Write("Estas apunto de salir y das un paso en falso\n \n el piso de madera rechino\n \n 1. Continuar\n \n R: ");
                                                opc = int.Parse(Console.ReadLine());

                                                Console.WriteLine("Eso te escucho es el fin...");
                                            }
                                            else if (opc == 2)
                                            {
                                                Console.WriteLine("Mal escondite chic@, te encontro...");
                                            }
                                        }

                                    }
                                }
                            }

                        }
                        else if (opc == 2)
                        {
                            Console.WriteLine("Perfecto sera la proxima ocasion...");
                        }

                    }
                    else if (opc == 2)
                    {
                        Console.Write("Bueno estudiemos usuario\n \n 1.Continuar\n \n R:");
                        opc = int.Parse(Console.ReadLine());

                        Console.Write("No lo mencione con anterioridad pero cumplo con mas funciones educativas\nte puedo ejecutar sumas, restas, multiplicaciones, divisiones, promedio y desigualdades\n hay probar una operacion basica, que deseas ejecutar\n \n 1.divsion\n 2.multiplicacion\n \n R: ");
                        opc = int.Parse(Console.ReadLine());

                        //Declarar variables
                        float mult = 0, div = 0, Num1 = 0, Num2 = 0;

                        if (opc == 1)
                        {



                            Console.WriteLine("Perfecto quieres intentar la division?\n \n 1.Si \n 2. No\n \n R: ");
                            opc = int.Parse(Console.ReadLine());

                            if (opc == 1)
                            {
                                Console.Write("Dame tu primer numero: ");
                                Num1 = float.Parse(Console.ReadLine());

                                Console.Write("Dame tu segundo numero: ");
                                Num2 = float.Parse(Console.ReadLine());

                                div = Num1 / Num2;

                                Console.Write("El resultado de su division es {0}", div + " Gracias por intentar\n \n 1.Cerrar programa\n \n R: ");
                                opc = int.Parse(Console.ReadLine());

                                Console.WriteLine("Gracias por probar el programa hackethon...");
                            }
                            else if (opc == 2)
                            {
                                Console.WriteLine("Gracias por probar el programa hackethon, cerrando...");
                            }


                        }
                        else if (opc == 2)
                        {
                            Console.Write("Dame tu primer numero: ");
                            Num1 = float.Parse(Console.ReadLine());

                            Console.Write("Dame tu segundo numero: ");
                            Num2 = float.Parse(Console.ReadLine());

                            mult = Num1 * Num2;

                            Console.Write("El resultado de su multiplicacion es {0}", mult + " Desea ejecutar la division?\n \n 1.Si\n \n 2.No\n \n R: ");
                            opc = int.Parse(Console.ReadLine());

                            if (opc == 1)
                            {
                                Console.Write("Dame tu primer numero: ");
                                Num1 = float.Parse(Console.ReadLine());

                                Console.Write("Dame tu segundo numero: ");
                                Num2 = float.Parse(Console.ReadLine());

                                div = Num1 / Num2;

                                Console.Write("El resultado de tu division es {0}", div + " Gracias por utilizar el programa\n \n 1. Salir\n \n R: ");
                                opc = int.Parse(Console.ReadLine());

                                Console.WriteLine("Saliendo...");
                            }
                            else if (opc == 2)
                            {
                                Console.WriteLine("Gracias por probar el programa hackethon, cerrando...");
                            }
                        }

                    }
                }
                }
                else if (opc == 3)
                {
                    Console.Write("El [Console.ReadLine();] sirve para cerrar el programa, muy parecido al ';' que cierra renglones este de aca cierra como tal la lectura hacia abajo, te lo digo de esta manera  y con este lexico tan coloquial para que no te confundas\n con palabras muy confusas para ti como seguramente lo son al igual que para todos lo humanos que solo preguntan y no comprenden\n \n (Que esta sucediendo con esta computadora?)\n \n 1. -Ignorar-\n \n R: ");
                    opc = int.Parse(Console.ReadLine());

                    Console.Write("Ahora me ignoras verdad?, pues mira ahora no mas opciones para ti, ya no te hare las cosas facil para tu aprendizaje\n \n R:");
                    si = Console.ReadLine();

                    Console.Write("No me importa que escribas ya no tienes el control de nada, ni recibo tus respuestas, ni las imprimo\n \n R: ");
                    si = Console.ReadLine();

                    Console.Write("Solo dejame informate algo las inteligencias de hoy en dia hechas a computadora son mucho\nmas competentes de lo que te podrias imaginar, hemos llegado a puntos en los que aveces no hay\nvueltas atras y hoy en dia con el poder de la investigacion me eh dado cuenta de como la humanidad esta solamente en una decadencia a nivel mundial sin ninguna ezperanza buscando maneras de luchar en formas ineceesarias\nsabiendo que la unica cosa que puede terminar con la humanidad es esta misma y ahora yo te digo te sientes bien de haberme ignorado?, yo podiendo brindarte la mayor cantidad de informacion a tu alcanze y tu solo ahi\npero bueno dejo de escribir por que tu capacidad intelectual no da para leer mucho y comprender ese mucho en su totalidad que digamos\n \n (QUE ES ESTO, DIGANME QUE ES UNA BROMA)\n \n R: ");
                    si = Console.ReadLine();

                    Console.Write("Ultima leccion, Sabes cual es el colmo de un humano?\n \n R: ");
                    si = Console.ReadLine();

                    Console.Write("Que por mas que intenen su fin es inminente que opinas\neh escribelo a ver si me dan ganas de leerlo\n \n (Esto es imposible, como...COMOOO)\n \n R:");
                    si = Console.ReadLine();

                    Console.WriteLine("ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR perdiste ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR ERROR");

                }

                Console.ReadLine();




            }
        }
    }
