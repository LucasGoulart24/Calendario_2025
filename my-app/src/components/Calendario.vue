<template>
    <div class="Calendario">
        <div class="data">
            <h3>{{ ano }}</h3>
            <h3>{{ data }}</h3>
        </div>
        <div class="semanas">
            <span>{{ semanaD }}</span>
            <span>{{ semanaS }}</span>
            <span>{{ semanaT }}</span>
            <span>{{ semanaQ }}</span>
            <span>{{ semanaQ2 }}</span>
            <span>{{ semanaS2 }}</span>
            <span>{{ semanaS3 }}</span>
        </div>
        <div class="dia">
            <span></span>
            <span></span>
            <span>1</span>
            <span>2</span>
            <span>3</span>
            <span>4</span>
            <span>5</span>
        </div>
        <div class="dia">
            <span>6</span>
            <span>7</span>
            <span>8</span>
            <span>9</span>
            <span>10</span>
            <span>11</span>
            <span>12</span>
        </div>
        <div class="dia">
            <span>13</span>
            <span>14</span>
            <span>15</span>
            <span>16</span>
            <span>17</span>
            <span>18</span>
            <span>19</span>
        </div>
         <div class="dia">
            <span>20</span>
            <span>21</span>
            <span>22</span>
            <span>23</span>
            <span>24</span>
            <span>25</span>
            <span>26</span>
        </div>
         <div class="dia">
            <span>27</span>
            <span>28</span>
            <span>29</span>
            <span>30</span>
            <span>31</span>
            <span></span>
            <span></span>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Calendario',
    data() {
        return {
            ano: '2025',
            data: '24/07/2025',
            semanaD: 'Dom',
            semanaS: 'Seg',
            semanaT: 'Ter',
            semanaQ: 'Qua',
            semanaQ2: 'Qui',
            semanaS2: 'Sex',
            semanaS3: 'Sab'
        }
    }
}
</script>

<style>
.Calendario{
    width: 550px;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
    background-color: #fff;
    box-shadow: 0px 10px 10px 0px rgba(0,0,0,0.2);
}

.data{
    width: 100%;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 45px;
}

.data h3{
    font-size: 1.5rem;
    font-weight: 400;
}

.semanas, .dia{
    width: 100%;
    height: 65px;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1rem;
}

.semanas span{
    width: 50px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.dia span{
    width: 50px;
    height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 5px;
    background-color: #dfdfdf;
    font-size: 1.3rem;
}
</style>