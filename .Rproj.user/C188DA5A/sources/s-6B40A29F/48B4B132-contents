### File R/zzz.R
### Part of the R package SBSR
### Copyright Behavioral Economics and Data Science Team (BEST)

### It is made available under the terms of the GNU General Public
### License, version 2, or at your option, any later version,
### incorporated herein by reference.
###
### This program is distributed in the hope that it will be
### useful, but WITHOUT ANY WARRANTY; without even the implied
### warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR
### PURPOSE.  See the GNU General Public License for more
### details.
###
### You should have received a copy of the GNU General Public
### License along with this program; if not, write to the Free
### Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
### MA 02110-1301, USA


.onAttach <- function(lib, pkg,...){
    packageStartupMessage(BESTWelcomeMessage())
}

BESTWelcomeMessage <- function(){

 paste("\n",
        "Bienvenidos al paquete SBSR version ", packageDescription("SBSR")$Version, "\n",
        "\n",
        "Conozca mas de los cursos, proyectos y otros servicios de BEST\n",
        "en nuestra pagina web:\n",
        "https://http://besteamperu.org/\n",
       "y nuestra pagina de github:\n",
       "https://github.com/BESTDATASCIENCE\n",
        "\n",
        "Para suprimir este mensaje use:\n",
        "suppressPackageStartupMessages(library(SBSR))\n",
          sep="")
}
