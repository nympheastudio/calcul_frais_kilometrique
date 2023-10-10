<!DOCTYPE html>
<html>
<head>
    <title>Calcul des frais kilométriques</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
    <script type="text/javascript">
        $(document).ready(function() {

            //code written by gouv in https://bmly.impots.gouv.fr/shS694.js?2

            const plages = {
                "vehicules_thermiques_a_hydrogene_ou_hybrides": null,
                "vehicules_thermiques_a_hydrogene_ou_hybrides_automobile": null,
                "vehicules_thermiques_a_hydrogene_ou_hybrides_automobile_3_cv_et_moins": [{
                    "coef_1": "0.529",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.316",
                    "coef_2": "1065",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.37",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_automobile_4_cv": [{
                    "coef_1": "0.606",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.34",
                    "coef_2": "1330",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.407",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_automobile_5_cv": [{
                    "coef_1": "0.636",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.357",
                    "coef_2": "1395",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.427",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_automobile_6_cv": [{
                    "coef_1": "0.665",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.374",
                    "coef_2": "1457",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.447",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_automobile_7_cv_et_plus": [{
                    "coef_1": "0.697",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.394",
                    "coef_2": "1515",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.47",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_deux_roues_plus_50cm3": null,
                "vehicules_thermiques_a_hydrogene_ou_hybrides_deux_roues_plus_50cm3_1_ou_2_cv": [{
                    "coef_1": "0.395",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.099",
                    "coef_2": "891",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.248",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_deux_roues_plus_50cm3_3_a_5_cv": [{
                    "coef_1": "0.468",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.082",
                    "coef_2": "1158",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.275",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_deux_roues_plus_50cm3_plus_de_5_cv": [{
                    "coef_1": "0.606",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.079",
                    "coef_2": "1583",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.343",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }],
                "vehicules_thermiques_a_hydrogene_ou_hybrides_deux_roues_moins_50cm3": [{
                    "coef_1": "0.315",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.079",
                    "coef_2": "711",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.198",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }],
                "vehicules_electriques": null,
                "vehicules_electriques_automobile": null,
                "vehicules_electriques_automobile_3_cv_et_moins": [{
                    "coef_1": "0.635",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.379",
                    "coef_2": "1278",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.444",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_electriques_automobile_4_cv": [{
                    "coef_1": "0.727",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.408",
                    "coef_2": "1596",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.488",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_electriques_automobile_5_cv": [{
                    "coef_1": "0.763",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.428",
                    "coef_2": "1674",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.512",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_electriques_automobile_6_cv": [{
                    "coef_1": "0.798",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.449",
                    "coef_2": "1748",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.536",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_electriques_automobile_7_cv_et_plus": [{
                    "coef_1": "0.836",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "5000"
                }, {
                    "coef_1": "0.473",
                    "coef_2": "1818",
                    "plage_debut": "5001",
                    "plage_fin": "20000"
                }, {
                    "coef_1": "0.564",
                    "coef_2": "0",
                    "plage_debut": "20001",
                    "plage_fin": null
                }],
                "vehicules_electriques_motocyclette_plus_4_kw_": null,
                "vehicules_electriques_motocyclette_plus_4_kw__1_ou_2_cv": [{
                    "coef_1": "0.474",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.119",
                    "coef_2": "1069",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.298",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }],
                "vehicules_electriques_motocyclette_plus_4_kw__3_a_5_cv": [{
                    "coef_1": "0.562",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.098",
                    "coef_2": "1390",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.33",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }],
                "vehicules_electriques_motocyclette_plus_4_kw__plus_de_5_cv": [{
                    "coef_1": "0.727",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.095",
                    "coef_2": "1900",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.412",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }],
                "vehicules_electriques_cyclomoteur___4_kw_": [{
                    "coef_1": "0.378",
                    "coef_2": "0",
                    "plage_debut": "0",
                    "plage_fin": "3000"
                }, {
                    "coef_1": "0.095",
                    "coef_2": "853",
                    "plage_debut": "3001",
                    "plage_fin": "6000"
                }, {
                    "coef_1": "0.238",
                    "coef_2": "0",
                    "plage_debut": "6001",
                    "plage_fin": null
                }]
            };


            let full_machine_name = [];
            
            $('.level').not(".level-0").hide();
            $("#simulateur-form-wrapper").hide();

            $(".step-block.first-step input").on("focus click touchstart", function(event) {
                let selectedStep = $(this).parent();

                $(".step-block.first-step").removeClass("active-step");
                $(selectedStep).addClass("active-step");
                $(".child-step").hide();
                $('.level-1').show();
                $(".step-block.child-step").removeClass("active-step");
                let targetId = $(selectedStep).data('id');
                $(".step-parent-" + targetId).show("slow");
                $(".step-parent-" + targetId + " input:first").prop("checked", true);
                scrollTo($(".level-0"));

                full_machine_name = [];
                full_machine_name[0] = $(selectedStep).data('m-name');
                
                $('.level-title').hide();

                let level = 0;
                for (let index = 0; index <= level + 1; index++) {
                    $('.level-title-' + index).show();
                }
                $("#simulateur-form-wrapper").hide();
            });

            $(".step-block.child-step input").on("click", function(event) {

                let selectedStep = $(this).parent();
                let level = $(selectedStep).data('level');
                let targetId = $(selectedStep).data('id');
                var nextLevel = level + 1;

                $('.level-title').hide();

                full_machine_name[level] = $(selectedStep).data('m-name');
                full_machine_name[level + 1] = "end";

                $("#input-step-id").val(targetId);
                $(".level-" + level + " .step-block.child-step").removeClass("active-step");

                $(selectedStep).addClass("active-step");
                $('.level-' + nextLevel + ' .child-step').hide();
                
                if ($(selectedStep).data('has-children')) {
                    initUI();
                    $("#simulateur-form-wrapper").show("slow");
                } else {
                    $("#simulateur-form-wrapper").hide();
                    if ($(".step-parent-" + targetId)[0]) {
                       
                        $('.level-' + nextLevel).show();
                        $(".step-parent-" + targetId).show("slow");
                        for (let index = 0; index <= level + 1; index++) {
                            $('.level-title-' + index).show();
                        }

                        scrollTo($(".level-" + nextLevel));
                    }
                }
            });

            /*=============== CALCUL Automobile =======================/
            /=========================================================*/
            function calculFraisKilometrique(puissance, dist) {
                let montant = 0;
                let distance = parseInt(dist);

                //debug
                console.log("puissance : " + puissance);
                console.log("distance : " + distance);


                $.each(plages, function(key, baremes) {
                    //debug
                    console.log("key : " + key);

                    if (puissance == key) {
                        montant = calculMontant(distance, baremes);
                    }
                });
                showMontant(montant);

            }

            /*============== CALCUL MONTANT ============================/
            /==========================================================*/
            function calculMontant(distance, baremes) {

                if (baremes.length == 1) {
                    if (distance >= baremes[0].plage_debut && distance <= baremes[0].plage_fin) {
                        montant = (distance * parseFloat(baremes[0].coef_1) + parseFloat(baremes[0].coef_2));
                    }
                } else if (baremes.length > 1) {

                    $.each(baremes, function(key, bareme) {
                        if (
                            ((distance >= parseFloat(bareme.plage_debut)) && (bareme.plage_fin == null)) ||
                            ((distance >= parseFloat(bareme.plage_debut)) && (distance <= parseFloat(bareme.plage_fin)))
                        ) {
                            montant = (distance * parseFloat(bareme.coef_1) + parseFloat(bareme.coef_2));
                        }
                    });

                }
                return montant;
            }

            /*============= CALCUL FraisKilometrique ===================/
            /==========================================================*/
            $("#btn_calculer").click(function() {

                let puissance = getPuissance(full_machine_name);
                let distance = $('input[name=distance]').val();
                //debug
                console.log("puissance : " + puissance);
                console.log("distance : " + distance);


                calculFraisKilometrique(puissance, distance);


                $("#montant").focus();
                return false;
            });

            function getPuissance(full_machine_name) {
                let puissance = "";

                let full_machine_name_string = full_machine_name.join("_");
                puissance = full_machine_name_string.substring(0, full_machine_name_string.indexOf("_end"));

                return puissance;
            }
            /*=================== AFFICHAGE MONTANT ====================/
            /==========================================================*/
            function showMontant(montant) {
                let decimalMontant = Number(montant.toString().match(/^\d+(?:\.\d{0,2})?/));
                $("#montant").html(Math.round(decimalMontant) + " €");
                $(".simulateur-form-result").show("slow");
            }

            function initUI() {
                $("input[name='distance']").val("");
                $("#montant").html("0 €");
            }

            function scrollTo(element) {
                $('html, body').animate({
                    scrollTop: $(element).offset().top
                }, 1000);
            }

        });
    </script>
</head>

<body>
    <div class="container">
        <h1>Calcul des frais kilométriques</h1>
        <div class="simulateur-wrapper">
            <fieldset class="level level-0">
                <legend style="display: none">Calcul des Frais kilométriques</legend>
                <div class="row mr-0">
                    <div class="step-block first-step col-sm-3 step-parent step-parent-0" data-id="4335" data-level="0" data-m-name="vehicules_thermiques_a_hydrogene_ou_hybrides">
                        <input class="step-block-input" id="input-step-4335" type="radio" name="step0" value="vehicules_thermiques_a_hydrogene_ou_hybrides" data-value="Véhicules thermiques, à hydrogène ou hybrides">
                        <label class="label-step" for="input-step-4335">Véhicules thermiques, à hydrogène ou hybrides
                        </label>
                    </div>
                    <div class="step-block first-step col-sm-3 step-parent step-parent-0 active-step" data-id="4347" data-level="0" data-m-name="vehicules_electriques">
                        <input class="step-block-input" id="input-step-4347" type="radio" name="step0" value="vehicules_electriques" data-value="Véhicules électriques">
                        <label class="label-step" for="input-step-4347">Véhicules électriques
                        </label>
                    </div>
                </div>
            </fieldset>
            <fieldset class="level level-1" style="">
                <legend style="display: none">Calcul des Frais kilométriques</legend>
                <p class="level-title level-title-1" style="display: none;">Votre moyen de transport :</p>
                <div class="row mr-0">
                    <div class="step-block child-step col-sm-3 step-parent step-parent-4335" data-id="4336" data-level="1" data-m-name="automobile" style="display: none;">
                        <input class="step-block-input" id="input-step-4336" type="radio" name="step1" value="automobile" data-value="Automobile">
                        <label class="label-step" for="input-step-4336">Automobile
                        </label>
                    </div>
                    <div class="step-block child-step col-sm-3 step-parent step-parent-4335" data-id="4342" data-level="1" data-m-name="deux_roues_plus_50cm3" style="display: none;">
                        <input class="step-block-input" id="input-step-4342" type="radio" name="step1" value="deux_roues_plus_50cm3" data-value="Deux roues > 50cm3">
                        <label class="label-step" for="input-step-4342">Deux roues &gt; 50cm3
                        </label>
                    </div>
                    <div class="step-block child-step col-sm-3 step-parent step-parent-4335" data-id="4346" data-level="1" data-m-name="deux_roues_moins_50cm3" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4346" type="radio" name="step1" value="deux_roues_moins_50cm3" data-value="Deux roues < 50cm3">
                        <label class="label-step" for="input-step-4346">Deux roues &lt; 50cm3
                        </label>
                    </div>
                    <div class="step-block child-step col-sm-3 step-parent step-parent-4347 active-step" data-id="4348" data-level="1" data-m-name="automobile" style="">
                        <input class="step-block-input" id="input-step-4348" type="radio" name="step1" value="automobile" data-value="Automobile">
                        <label class="label-step" for="input-step-4348"> Automobile
                        </label>
                    </div>
                    <div class="step-block child-step col-sm-3 step-parent step-parent-4347" data-id="4354" data-level="1" data-m-name="motocyclette_plus_4_kw_" style="">
                        <input class="step-block-input" id="input-step-4354" type="radio" name="step1" value="motocyclette_plus_4_kw_" data-value="Motocyclette (> 4 kW)">
                        <label class="label-step" for="input-step-4354">Motocyclette (&gt; 4 kW)
                        </label>
                    </div>
                    <div class="step-block child-step col-sm-3 step-parent step-parent-4347" data-id="4358" data-level="1" data-m-name="cyclomoteur___4_kw_" data-has-children="no" style="">
                        <input class="step-block-input" id="input-step-4358" type="radio" name="step1" value="cyclomoteur___4_kw_" data-value="Cyclomoteur (≤ 4 kW)">
                        <label class="label-step" for="input-step-4358">Cyclomoteur (≤ 4 kW)
                        </label>
                    </div>
                </div>
            </fieldset>
            <fieldset class="level level-2" style="">
                <legend style="display: none">Calcul des Frais kilométriques</legend>
                <p class="level-title level-title-2" style="display: none;">Puissance administrative :</p>
                <div class="row mr-0">
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4336" data-id="4337" data-level="2" data-m-name="3_cv_et_moins" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4337" type="radio" name="step2" value="3_cv_et_moins" data-value="3 CV et moins">
                        <label class="label-step" for="input-step-4337">
                            3 CV et moins
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4336" data-id="4338" data-level="2" data-m-name="4_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4338" type="radio" name="step2" value="4_cv" data-value="4 CV">
                        <label class="label-step" for="input-step-4338">
                            4 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4336" data-id="4339" data-level="2" data-m-name="5_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4339" type="radio" name="step2" value="5_cv" data-value="5 CV">
                        <label class="label-step" for="input-step-4339">
                            5 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4336" data-id="4340" data-level="2" data-m-name="6_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4340" type="radio" name="step2" value="6_cv" data-value="6 CV">
                        <label class="label-step" for="input-step-4340">
                            6 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4336" data-id="4341" data-level="2" data-m-name="7_cv_et_plus" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4341" type="radio" name="step2" value="7_cv_et_plus" data-value="7 CV et plus">
                        <label class="label-step" for="input-step-4341">
                            7 CV et plus
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4342" data-id="4343" data-level="2" data-m-name="1_ou_2_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4343" type="radio" name="step2" value="1_ou_2_cv" data-value="1 ou 2 CV">
                        <label class="label-step" for="input-step-4343">
                            1 ou 2 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4342" data-id="4344" data-level="2" data-m-name="3_a_5_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4344" type="radio" name="step2" value="3_a_5_cv" data-value="3 à 5 CV">
                        <label class="label-step" for="input-step-4344">
                            3 à 5 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4342" data-id="4345" data-level="2" data-m-name="plus_de_5_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4345" type="radio" name="step2" value="plus_de_5_cv" data-value="Plus de 5 CV">
                        <label class="label-step" for="input-step-4345">
                            Plus de 5 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4348" data-id="4349" data-level="2" data-m-name="3_cv_et_moins" data-has-children="no" style="">
                        <input class="step-block-input" id="input-step-4349" type="radio" name="step2" value="3_cv_et_moins" data-value="3 CV et moins">
                        <label class="label-step" for="input-step-4349">
                            3 CV et moins
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4348 active-step" data-id="4350" data-level="2" data-m-name="4_cv" data-has-children="no" style="">
                        <input class="step-block-input" id="input-step-4350" type="radio" name="step2" value="4_cv" data-value="4 CV">
                        <label class="label-step" for="input-step-4350">
                            4 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4348" data-id="4351" data-level="2" data-m-name="5_cv" data-has-children="no" style="">
                        <input class="step-block-input" id="input-step-4351" type="radio" name="step2" value="5_cv" data-value="5 CV">
                        <label class="label-step" for="input-step-4351">
                            5 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4348" data-id="4352" data-level="2" data-m-name="6_cv" data-has-children="no" style="">
                        <input class="step-block-input" id="input-step-4352" type="radio" name="step2" value="6_cv" data-value="6 CV">
                        <label class="label-step" for="input-step-4352">
                            6 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4348" data-id="4353" data-level="2" data-m-name="7_cv_et_plus" data-has-children="no" style="">
                        <input class="step-block-input" id="input-step-4353" type="radio" name="step2" value="7_cv_et_plus" data-value="7 CV et plus">
                        <label class="label-step" for="input-step-4353">
                            7 CV et plus
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4354" data-id="4355" data-level="2" data-m-name="1_ou_2_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4355" type="radio" name="step2" value="1_ou_2_cv" data-value="1 ou 2 CV">
                        <label class="label-step" for="input-step-4355">
                            1 ou 2 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4354" data-id="4356" data-level="2" data-m-name="3_a_5_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4356" type="radio" name="step2" value="3_a_5_cv" data-value="3 à 5 CV">
                        <label class="label-step" for="input-step-4356">
                            3 à 5 CV
                        </label>
                    </div>
                    <div class="step-block child-step child-item col-sm-2 step-parent step-parent-4354" data-id="4357" data-level="2" data-m-name="plus_de_5_cv" data-has-children="no" style="display: none;">
                        <input class="step-block-input" id="input-step-4357" type="radio" name="step2" value="plus_de_5_cv" data-value="Plus de 5 CV">
                        <label class="label-step" for="input-step-4357">
                            Plus de 5 CV
                        </label>
                    </div>
                </div>
            </fieldset>

            <div class="row" id="simulateur-form-wrapper" style="">
                <div class="col-md-6">
                    <div class="simulateur-form">
                        <p class="simulateur-form-message">Prix de revient (frais de garage exclus). Indiquez :</p>
                        <div class="form-group">
                            <label for="distance">*
                                Le kilométrage effectué dans l'année :</label>
                            <input type="number" id="distance" class="form-control" name="distance" maxlength="6" required="">
                        </div>
                        <button type="submit" id="btn_calculer" class="btn btn-default calculate" aria-controls="montant">CALCULER MES FRAIS</button>

                    </div>
                </div>
                <div class="col-md-6">
                    <div class="simulateur-form-result-wrapper">
                        <div class="simulateur-form-result" style="display: block;">
                            <p class="result-message">Le montant de vos frais kilométriques s'élève à :</p>
                            <p class="result-montant-wrapper">
                                <span id="montant" aria-live="assertive">0 €</span>
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
</body>

</html>